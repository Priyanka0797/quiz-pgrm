# studentDetails
https://github.com/Priyanka0797/student Details.git
import scanner
import java.util.Scanner;

Public class StudentDetails{
Public static void main(String[]args){
Public static List<data> get CartList(){
JSONObject responseDetailsJson = new JSONObject();
JSONArray jsonArray = new JSONArray();
List<data> cartList = new Vector<data>(cartMap.keySet().size());
for(data d:cartMap.keySet()){
cartList.add(d);
JSONObject studDetailsJson = new JSONObject();
studDetailsJson.put("id","101");
studDetailsJson.put("name","nethu");
jsonArray.add(studDetailsJson);
}
responseDetailsJson.put("StudentDetails",jsonArray);
return cartList;
}
ArrayList<String>subject = new ArrayList<String>();
subject.add("EVS");
subject.add("POWER ELECTRONICS");
subject.add("LIC");
subject.add("MATHS");
subject.add("DSP");
log("Raw ArrayList" + subject);
GsonBuilder gsonBuilder = new GsonBuilder();
Gson gson =gsonBuilder = gson.toHson(subject);
log("/nConverted JSONObject" + JSONObject);
Gson prettyGson = new GsonBuilder().setPrettyPrinting().create();
String PrettyJson = prettyGson.toJson(subject);
log("/nPretty JSONObject"prettyJson);
}
Private static void log (Object print){
System.out.println(print);
}
}
}

