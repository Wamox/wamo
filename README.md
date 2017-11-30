# wamo
 int Number = 25;
          int rem = 0;
        string binary = "";

        do 
        {
        rem = Number % 2;
        binary = (binary + rem);
        Number = Number / 2;
        } while (Number > 1);

      binary = Number + binary;
      Console.Writeline(binary);
      Console.Readline();
}
}
}
