# Funções C#
Funções variadas para usar em C#

string nome_extrato = $"extrato{DateTime.Now}";

Inicia uma variável string (nome_extrato)


string temp = nome_extrato.Replace(" ", "").Replace(":", "").Replace("/", "");

o nome da variável e .Replace()

dentro dos parênteses vem primeiro oque vc vai apagar e pelo oque vai ser substituido ex.("Vou apagar", "Vou subistituir por")

using (StreamWriter escrever = new StreamWriter(temp + ".txt")

                                                concatena a variavel criada para um arquivo .txt