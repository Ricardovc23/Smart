void main() {
  Map<int, String> smart =
  {
    101: "pab blanco",
    101: "galon de leche",
    101: "papitas",
  };//fin mapa smart
  
  print(smart);
  
  for(int codigo in smart.keys){
    print(codigo);
    
  }//fin for codigo
  
  for(String articulo in smart.values){
    print(articulo);
  }//fin for codigo 
  
  Map<String, double> papeleria =
  {
    104: "lapiz : 2.00",
  };
   print(papeleria); 
}
