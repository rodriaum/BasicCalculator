# Calculadora B�sica em Windows Forms C#

Esta � uma calculadora b�sica implementada em C# usando Windows Forms. A calculadora suporta opera��es b�sicas como adi��o, subtra��o, multiplica��o e divis�o.

## Funcionalidades

- Adi��o de dois n�meros.
- Subtra��o de dois n�meros.
- Multiplica��o de dois n�meros.
- Divis�o de dois n�meros.

## Requisitos

- Visual Studio (ou qualquer outra IDE que suporte o desenvolvimento de aplicativos Windows Forms em C#).

## Como usar

1. Clone ou fa�a o download deste reposit�rio para o seu computador.
2. Abra o projeto no Visual Studio.
3. Execute o projeto.
4. A calculadora ser� exibida.
5. Insira os n�meros nos campos apropriados.
6. Selecione a opera��o desejada.
7. Clique no bot�o "=".
8. O resultado ser� exibido na tela.

## Estrutura do Projeto

- `FormCalculator.cs`: Cont�m a l�gica principal da aplica��o.
- `FormCalculator.Designer.cs`: Cont�m o c�digo gerado automaticamente pelo Visual Studio para definir a interface do usu�rio.
- `Program.cs`: Arquivo de inicializa��o do aplicativo.

## Exemplo de Uso de Arrays Double

Este projeto utiliza arrays de double para armazenar os n�meros inseridos pelo usu�rio. A classe `MathOperator.cs` � respons�vel por acessar esses arrays e realizar a opera��o selecionada.

```csharp
    public double[] numbers { get; set; }

    double total = -1;

    switch (charOperator)
    {
        case "+":
            total = mathOperator.Add(numbers);
            break;

        case "-":
            total = mathOperator.Subtract(numbers);
            break;

        case "�":
            total = mathOperator.Multiply(numbers);
            break;

        case "�":
            total = mathOperator.Divide(numbers);
            break;
    }
```

## Licen�a

Este projeto est� licenciado sob a Licen�a MIT - consulte o arquivo [LICENSE](https://github.com/rodriaum/BasicCalculator?tab=MIT-1-ov-file#MIT-1-ov-file) para obter detalhes.
