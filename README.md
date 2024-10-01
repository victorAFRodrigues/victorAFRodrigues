<img width=100% style="cursor:auto" src="https://capsule-render.vercel.app/api?type=waving&color=052252&height=120&section=header"/>

<!-- [![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=FFF&size=35&center=true&vCenter=true&width=1000&lines=Hi,+My+name+is+Victor+Rodrigues!!;I'm+20+years+old;I+from+Brasil,+São+Paulo;Be+Welcome!+:%29)](https://git.io/typing-svg) -->
[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=FFF&size=35&center=true&vCenter=true&width=1000&lines=Be+Welcome!+:%29)](https://git.io/typing-svg)

<br/><br/>
```typescript
interface Language {
    name: string;
    knowledge_level: 'beginner' | 'intermediate' | 'advanced' | 'fluent' | 'native';
};
interface Tool {
    language_name: string;
    tools_and_frameworks: Array<Language>;
}
interface Database {
    type: 'SQL' | 'NoSQL',
    databases: Array<Language>;
}
interface Person {
    age: number|string;
    pronouns: string;
    languages: Array<Language>;
    programing_languages: Array<Language>;
    tools: Array<Tool>;
    databases: Array<Database>;
    career_objective: string;
}
const Me:Person = {
    age: '20y',
    pronouns: 'He | Him',
    languages: [
        { name: 'English', knowledge_level: 'beginner' },
        { name: 'Portuguese', knowledge_level: 'native' }
    ],
    programing_languages: [
        { name: 'JavaScript', knowledge_level: 'intermediate' },
        { name: 'PHP', knowledge_level: 'intermediate' },
        { name: 'Python', knowledge_level: 'intermediate' },
        { name: 'TypeScript', knowledge_level: 'beginner' },
        { name: 'Java', knowledge_level: 'beginner' }
    ],
    tools: [
        {
            language_name: 'JavaScript',
            tools_and_frameworks: [
                { name: 'React', knowledge_level: 'beginner' },
                { name: 'Jquery', knowledge_level: 'beginner' },
                { name: 'Node', knowledge_level: 'beginner' }
            ],
        },
        {
            language_name: 'PHP',
            tools_and_frameworks: [
                { name: 'Laravel', knowledge_level: 'beginner' },
                { name: 'Wordpress', knowledge_level: 'intermediate' }
            ],
        },
        {
            language_name: 'Python',
            tools_and_frameworks: [
                { name: 'Pyautogui', knowledge_level: 'beginner' },
                { name: 'Selenium', knowledge_level: 'beginner' }
            ],
        },
        {
            language_name: 'TypeScript',
            tools_and_frameworks: [
                { name: 'Angular', knowledge_level: 'intermediate' }
            ],
        },
    ],
    databases: [
        {
            type: 'SQL',
            databases:[
                { name: 'MySQL', knowledge_level: 'beginner'}
            ]
        },
        {
            type: 'NoSQL',
            databases:[
                { name: 'MongoDB', knowledge_level: 'beginner'}
            ]
        },
    ],
    career_objective: "My main goal is to be a thorough Web Developer!"
}
```

<hr>
<div align="center">  
  <img width="49%" height="195px" src="https://github-readme-stats.vercel.app/api?username=victorAFRodrigues&show_icons=true&count_private=true&hide_border=true&title_color=fff&icon_color=fff&text_color=fff&bg_color=344257" alt="victorAFRodrigues github stats" /> 
  <img width="41%" height="195px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=victorAFRodrigues&layout=compact&hide_border=true&title_color=fff&text_color=fff&bg_color=344257" />
</div>
<hr>
</div>

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=052252&height=120&section=footer"/>
