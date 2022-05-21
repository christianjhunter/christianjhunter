# <img src="https://media.giphy.com/media/ObNTw8Uzwy6KQ/giphy.gif" width="30px">&nbsp; Hi, I’m Christian Hunter (@christianjhunter)

<a href="https://www.linkedin.com/in/christianjhunter/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;

```typescript
class ChristianHunter extends Human {

  public readonly languages: string[];
  public readonly tools: Tool[];
  public readonly currentJob: Job;
  
  public constructor() {
    this.languages = ['Java', 'Python', 'Typescript', 'Javascript'];
    this.tools = [Node, React, NextJs, Redux, Django, AWS, AWS_CDK, Docker];
    
    this.currentJob = new Job({
      company: 'Google',
      role: 'Software Engineer',
      team: 'Youtube'
    }); 
  }
    
  public getFunFact(): string {
    return 'Fullmetal Alchemist is my favorite anime!'
  }
  
}
```

<!---
christianjhunter/christianjhunter is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
