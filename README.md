# Asesoria3b_23073

package review;

public class Text {

    public static void main(String[] args) {
        Person p = new Person(); // crear un objeto
        //
        p.setName("Marcos");
        p.setLastname("Rios");
        p.setAge((byte) 20);
        p.setHeigt(1.72f);
        p.setGender("En la cama");
        p.setWeight((short)90);
        System.out.println("name is " + p.getName()+"\n "+p.getLastname()+"\n"+p.getAge()+"\n"+p.getWeight()+"\n"+p.getGender()+"\n"+p.getWeight());
    }
    
}


/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package review;

/**
 *
 * @author PC-23
 */
public class Person {
    private String name,lastname,gender;
    private float heigt;
    private byte age;
    private short weight;
    public void setName(String name){//parametro //para poder asignar un valor al atributo  name
        this.name=name;
    }

    public void setLastname(String lastname) {
        this.lastname = lastname;
    }

    public void setGender(String gender) {
        this.gender = gender;
    }

    public void setHeigt(float heigt) {
        this.heigt = heigt;
    }

    public void setAge(byte age) {
        this.age = age;
    }

    public void setWeight(short weight) {
        this.weight = weight;
    }
    
     public String getName() {
        return name;
    }
     
    public String getGender(){
       return gender;
}
    public float getHeigt(){
       return heigt;
}
    public byte getAge(){
       return age;
}

    public String getLastname() {
        return lastname;
    }

    public short getWeight() {
        return weight;
    }
    
}
