# 👋 Hi there, I'm Srikanth Nani! 

```javascript
let skills = {
  programmingLanguages: ["Javascript", "TypeScript", "Java", "Python", "Go", "PHP"],
  webFrontEnd: ["HTML", "CSS", "Bootstrap", "Jquery", "ReactJs", "NextJs"],
  mobile: ["React Native", "Android Development", "XCode"],
  databases: ["MySQL", "PostgreSQL", "MongoDB"],
  additionalSkills: ["Firebase", "AWS Amplify", "Storybook", "Redux", "Detox", "React-Query", 
                     "Jest", "datadoghq", "Reanimated", "Git", "Styled Components", "Codepush",
                     "Auth0", "Sendbird"]
};

let tools = ["Adobe Photoshop", "Adobe Illustrator", "Figma"];
let os = ["Mac", "Linux", "Windows"];

let me = {
  name: "Srikanth Nani",
  role: "Software Developer",
  location: "Hyderabad, Telangana",
  languagesSpoken: ["Telugu", "English", "Hindi"],
  skills: skills,
  tools: tools,
  os: os
};

console.log(`
👨‍💻 Hello there, I'm ${me.name}!

📍 I'm a ${me.role} based in ${me.location}. I speak ${me.languagesSpoken.join(", ")} fluently.

👨‍💻 I've mastered programming languages like ${me.skills.programmingLanguages.join(", ")}, and I shape the web with technologies like ${me.skills.webFrontEnd.join(", ")}.

📱 For mobile application development, I prefer using ${me.skills.mobile.join(", ")}.

🗄️ In the world of databases, I've dipped my fingers in ${me.skills.databases.join(", ")}.

💼 Additionally, I have experience with ${me.skills.additionalSkills.join(", ")}.

🔧 I also use tools such as ${me.tools.join(", ")} and am comfortable with operating systems like ${me.os.join(", ")}.

💌 To learn more about me, you can shoot me an [email](mailto:srikanthnani1202@gmail.com)! 
`);
