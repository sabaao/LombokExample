This is a Lombok example project.
You don't generate getter and setter in a bean, you just add annotation, and Lombok will generate it.

#2 Install Lombok
Install Lombok jar and install it.
https://projectlombok.org/setup/eclipse

#2 Add annotation
Add @Data annotation on bean class, it will generate getter and setter by IDE(Ex: Eclipse).

#2 Build project and check
You can check IDE already generate getter and setter by "javap".
Go to terminal and change to Customer.class's folder, input "javap Customer.class".
You will see result.

#Reference
https://projectlombok.org/
