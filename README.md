 👋 Hi, I’m @arifaydogan

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
        skills.put("languages",  Arrays.asList(new Technology[]{new Java(), new JavaScript(), new Node(), new SQL(), new Pyhton()}));
        skills.put("databases",  Arrays.asList(new Technology[]{new MySql(), new Oracle(), new PostreSQL(), new Redis()}));
        skills.put("misc",       Arrays.asList(new Technology[]{new Docker(), new Kubernetes(), new RabbitMQ(), new Weblogic()}));
        skills.put("frameworks", Arrays.asList(new Technology[]{new Spring(), new JSF(), new Hibernate(), new Dropwizard()}));
        return skills;
    }
    
    public String getFutureGoal() {
        return "To live single and free like a tree, in fraternity like a forest...";
    }

}
```
