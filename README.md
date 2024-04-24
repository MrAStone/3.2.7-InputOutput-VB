<pre lang=vb.net>
Module Module1

    Sub Main()
        'Be able to obtain user input from the keyboard
        Dim input As String
        Console.Write("Enter something: ")
        input = Console.ReadLine ' always assigned as a string but VB will allow you to input into a number/boolean as well

        'Be able to output data and information from a program to the computer display
        Console.WriteLine(input)
    End Sub

End Module
