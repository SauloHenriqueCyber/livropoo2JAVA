# livropoo2JAVA


package com.mycompany.projetolivro;


public class projetolivro {
    
    public static void main(String[] args){
       Pessoa[] p = new Pessoa [2];
       Livro[] l= new Livro [3];       
    
    p[0] = new Pessoa("Pedro", 25, "Masculino");
    p[1] = new Pessoa("joão", 28, "Masculino");
    
    l[0] = new Livro("O caçador de Pipas","josé saramago",60, "pedro");
    l[1] = new Livro("O monge","dom paton",400, "João");
    l[2] = new Livro("o ateneu","marlon",120, "Pedro");

     
    l[0].abrir();
    l[0].folhear(20);
    l[0].avancarPag();
    
    System.out.println(l[0].detalhes());
    System.out.println(l[1].detalhes());
    
    }
}
