using System;
using System.Collections.Generic;
using System.Configuration;
using System.Linq;
using System.Text;using System;

namespace Projeto_de_produto_de_super_mercado
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int precoDoProduto;

            // Mensagem para pedir o valor do produto
            string fraseDePergunta = "Digite o valor do produto:";

            // Mostra a mensagem para a pessoa
            Console.WriteLine(fraseDePergunta);

            precoDoProduto = int.Parse(Console.ReadLine());

            // Mostrando o preço do produto
            Console.WriteLine($"O preço do produto é de: {precoDoProduto}");
        }
    }
}
