using System.Linq;

void Update()
    {
        if (InventoryIsFull() == false)
        {
            // Your Code
        }
    }

private bool InventoryIsFull()
        {
            bool[] invIsFull = new bool[YourArray.Length];

            for (int i = 0; i < YourArray.GetLength(0); i++)
            {
                if (YourArray[i].isFull == true)
                    invIsFull[i] = true;
                else continue;
                
            }
            return invIsFull.All(x => x);
        }
