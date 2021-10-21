 ## 👋 Hi, I’m @arifaydogan <img src="https://user-images.githubusercontent.com/13220440/138233550-621b4372-99ed-4edd-8518-c04ab88dca80.jpg" width="25%" align="right">


  ![](https://img.shields.io/badge/Editor-IntellijIDEA-informational?style=flat&logo=intellijidea&logoColor=white&color=00aed8)
  ![](https://img.shields.io/badge/Code-Java-informational?style=flat&logo=java&logoColor=white&color=00aed8)
  ![](https://img.shields.io/badge/DB-postreSQL-informational?style=flat&logo=postgresql&logoColor=white&color=00aed8)
  ![](https://img.shields.io/badge/DB-Oracle-informational?style=flat&logo=oracle&logoColor=white&color=00aed8)
  ![](https://img.shields.io/badge/DB-MySQL-informational?style=flat&logo=mysql&logoColor=white&color=00aed8)
<br>
  ![](https://img.shields.io/badge/Tool-Docker-informational?style=flat&logo=docker&logoColor=white&color=00aed8)
  ![](https://img.shields.io/badge/Tool-Kubernetes-informational?style=flat&logo=kubernetes&logoColor=white&color=00aed8)
  ![](https://img.shields.io/badge/Tool-Redis-informational?style=flat&logo=redis&logoColor=white&color=00aed8)
  ![](https://img.shields.io/badge/Tool-RabbitMQ-informational?style=flat&logo=rabbitmq&logoColor=white&color=00aed8)
  ![](https://img.shields.io/badge/Tool-Kubernetes-informational?style=flat&logo=kubernetes&logoColor=white&color=00aed8)
   ![](https://img.shields.io/badge/Framework-Spring-informational?style=flat&logo=spring&logoColor=white&color=00aed8)
  ![](https://img.shields.io/badge/Automobile-Leon-informational?style=flat&logo=seat&logoColor=white&color=00aed8)
  ![](https://img.shields.io/badge/Social-/arifaydogan-informational?style=flat&logo=linkedin&logoColor=white&color=00aed8)
<br>
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
      skills.put("language", Arrays.asList(new Technology[]{new Java(), new JS(), new Node(), new SQL(), new Pyhton()}));
      skills.put("database", Arrays.asList(new Technology[]{new MySql(), new Oracle(), new PostreSQL(), new Redis()}));
      skills.put("misc",     Arrays.asList(new Technology[]{new Docker(), new Kubernetes(), new RabbitMQ()}));
      skills.put("framework",Arrays.asList(new Technology[]{new Spring(), new JSF(), new Dropwizard()}));
      //TODO : keep adding more...
      return skills;
    }
    
    public String getFutureGoal() {
        return "To live single and free like a tree, in fraternity like a forest...";
    }

}
```

![Arif's GitHub Stats](https://github-readme-stats.vercel.app/api?username=arifaydogan&show_icons=true)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=arifaydogan&layout=compact)](https://github.com/arifaydogan/)



