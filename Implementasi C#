namespace Soal2
{
    class RetailItem
    {
        private String description;
        private int unitsOnHand;
        private double price;
        // Constructor
        public RetailItem(String description, int unitsOnHand, double price)
        {
            this.description = description;
            this.unitsOnHand = unitsOnHand;
            this.price = price;
        }

        // Accessor Method
        public void setDescription(String description)
        {
            this.description = description;
        }

        public String getDescription()
        {
            return description;
        }

        public void setUnitsOnHand(int unitsOnHand)
        {
            this.unitsOnHand = unitsOnHand;
        }

        public int getUnitsOnHand()
        {
            return unitsOnHand;
        }

        public void setPrice(double price)
        {
            this.price = price;
        }

        public double getPrice()
        {
            return price;
        }
    }
}
namespace Soal2
{
    class Program
    {
        static void Main(string[] args)
        {
            RetailItem[] item = new RetailItem[3];
            item[0] = new RetailItem("Jacket", 12, 59.95);
            item[1] = new RetailItem("Jeans", 40, 34.95);
            item[2] = new RetailItem("Shirt", 20, 24.95);

            Console.WriteLine("---------------------------------------------");
            Console.WriteLine("\t|Description\t|UnitsOnHand\t|Price");
            Console.WriteLine("---------------------------------------------");
for(int i = 0; i < item.Length; i++)
            {
                Console.WriteLine("Item " + (i+1) + "\t|" + 
item[i].getDescription() + "\t\t|" + item[i].getUnitsOnHand() + "\t\t|$" + item[i].getPrice());
            }
            Console.WriteLine("---------------------------------");
            
            Console.ReadKey();
        }
    }
}
