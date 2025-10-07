package Exercicio2;
public class Funcionario {
   public String nome;
   public double salario;
   public double imposto;


   public double novoSalario() {
       return imposto * salario;
   }


   public void aumentarSalario(double imposto) {
       this.imposto += imposto;
   }


   public double valorTotalSalarioLiquido() {
       return salario * imposto;
   }


   @Override
   public String toString() {
       double salario = 1000.00;
       int imposto = 5;


       double valorImposto = salario * (imposto / 100.0);


       double salarioLiquido = salario + valorImposto;


       return String.format("Funcionario: %s " +
                       "\nSalario: R$ %.2f" +
                       "\nImposto: %d%%" +
                       "\nValor total do salario liquido: R$ %.2f",
               nome, salario, imposto, salarioLiquido);
   }
}

