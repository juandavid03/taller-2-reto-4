# taller-2-reto-4

    class Program
    
    {
        static void Main(string[] args)
        
        {
        
            int dia;
            
            string d = Console.ReadLine();
            
            dia = Convert.ToInt16(d);
            

            switch(dia)
            
            {
            
                case 1:
                
                    Console.WriteLine("domingo");
                    
                    break;
                    
                case 2:
                
                    Console.WriteLine("lunes");
                    
                    break;
                    
                case 3:
                
                    Console.WriteLine("martes");
                    
                    break;
                    
                case 4:
                
                    Console.WriteLine("miercoles");
                    
                    break;
                    
                case 5:
                
                    Console.WriteLine("jueves");
                    
                    break;
                    
                case 6:
                
                    Console.WriteLine("viernes");
                    
                    break;
                    
                case 7:
                
                    Console.WriteLine("sabado");
                    
                    break;
                    
            }
            
            Console.ReadLine();
            

        }
        
    }
    
}
