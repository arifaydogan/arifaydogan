 👋 Hi, I’m @arifaydogan

  ![](https://img.shields.io/badge/Editor-IntellijIDEA-informational?style=flat&logo=intellijidea&logoColor=white&color=2bbc8a)
  ![](https://img.shields.io/badge/Code-Java-informational?style=flat&logo=java&logoColor=white&color=2bbc8a)
  ![](https://img.shields.io/badge/DB-postreSQL-informational?style=flat&logo=postgresql&logoColor=white&color=2bbc8a)
  ![](https://img.shields.io/badge/DB-Oracle-informational?style=flat&logo=oracle&logoColor=white&color=2bbc8a)
  ![](https://img.shields.io/badge/DB-MySQL-informational?style=flat&logo=mysql&logoColor=white&color=2bbc8a)
  ![](https://img.shields.io/badge/Tool-Docker-informational?style=flat&logo=docker&logoColor=white&color=2bbc8a)
  ![](https://img.shields.io/badge/Tool-Kubernetes-informational?style=flat&logo=kubernetes&logoColor=white&color=2bbc8a)
  ![](https://img.shields.io/badge/Framework-Spring-informational?style=flat&logo=spring&logoColor=white&color=2bbc8a)
  
<code><img height="30" src="https://raw.githubusercontent.com/jmnote/z-icons/master/svg/java.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/jmnote/z-icons/master/svg/javascript.svg"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/vue/vue.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/cpp/cpp.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png"></code>

```java
package arifaydogan;

public class About extends Me implements SoftwareEngineer<ArifAydogan> {

    public static final String LINKEDIN = "https://www.linkedin.com/in/arifaydogan/";

    @Override
    public Education getEducationInfo() {
        return Education.builder()
                .name("Suleyman Demirel University (SDU)");
                .degree(Degrees.BSc);
                .department("Computer Engineering")
                .graduationYear(2014)
                .build();
    }

    @Override
    public Map<String, List<Technology>> getDeveloperSkills() {
        Map<String, List<Technology>> skills = new HashMap<>();
        skills.put("languages", Arrays.asList(new Technology[]{new Java(), new JS(), new Node(), new SQL(), new Pyhton()}));
        skills.put("databases", Arrays.asList(new Technology[]{new MySql(), new Oracle(), new PostreSQL(), new Redis()}));
        skills.put("misc",      Arrays.asList(new Technology[]{new Docker(), new Kubernetes(), new RabbitMQ()}));
        skills.put("frameworks",Arrays.asList(new Technology[]{new Spring(), new JSF(), new Dropwizard()}));
        return skills;
    }
    
    public String getFutureGoal() {
        return "To live single and free like a tree, in fraternity like a forest...";
    }

}
```

![Arif's GitHub Stats](https://github-readme-stats.vercel.app/api?username=arifaydogan&show_icons=true)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=arifaydogan&layout=compact)](https://github.com/arifaydogan/)



