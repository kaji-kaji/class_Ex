class StudentCard {  
  int id;   //学籍番号  
  String name;  //氏名  
}  

public class InstanceExample2 {  
  public static void main(String[] args) {  
    StudentCard a = new StudentCard();  
    a.id = 1234;  
    a.name = "鈴木太郎";  
    
    StudentCard b = new StudentCard();  
    b.id = 1235;  
    b.name = "佐藤花子";  
    
    System.out.println("aのidの値は" + a.id);  
    System.out.println("aのnameの値は" + a.name);  
    System.out.println("bのidの値は" + b.id);  
    System.out.println("bのnameの値は" + b.name);  
    
実行結果  
    
aのidの値は1234  
aのnameの値は鈴木太郎  
bのidの値は1235  
bのnameの値は佐藤花子  
