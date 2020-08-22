Option Strict On
Option Explicit On


Module variables


    Sub Main()
        Dim myFirstNumber As Integer
        Dim mySecondNumber As Integer
        Dim aLittleString As String
        Dim someSortOfTest As Boolean
        Dim result As Integer


        myFirstNumber = 42
        Console.WriteLine(myFirstNumber)
        Console.ReadLine()


        aLittleString = "some text"

        Console.WriteLine(aLittleString)
        Console.ReadLine()

        'someSortOfTest = True

        Console.WriteLine(someSortOfTest)
        Console.ReadLine()

        'x=7
        'Console.WriteLine(x)
        'Console.ReadLine()


        'do math

        myFirstNumber = 42
        mySecondNumber = 8

        Console.WriteLine(myFirstNumber + mySecondNumber)
        Console.ReadLine()

        result = myFirstNumber + mySecondNumber

        Console.WriteLine(result)
        Console.ReadLine()


    End Sub

End Module
