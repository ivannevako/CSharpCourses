public static double Calculate(string userInput)
        {
            string[] stringInputs = userInput.Split();
            double sum = double.Parse(stringInputs[0]);
            double proc = double.Parse(stringInputs[1]);
            double month = double.Parse(stringInputs[2]);


            double result = sum * (1 + proc / 12 / 100);
                return result;
        }