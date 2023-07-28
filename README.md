using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace LAUNDRY
{
    internal class menuList
    {
        string purchase;
        int kilogram;
        int liter;
        int scoop_of_powdered_detergent;
        int time;

        static void Main(int[] args)
        {
            menuList YunohOne = new menuList();
            YunohOne.kilogram = 5-9;
            YunohOne.liter = 3000;
            YunohOne.scoop_of_powdered_detergent = 3;
            YunohOne.time = 1;

            menuList YunohTwo = new menuList();
            YunohTwo.kilogram = 10-14;
            YunohTwo.liter = 6000;
            YunohTwo.scoop_of_powdered_detergent = 6;
            YunohTwo.time = 2;

            menuList YunohThree = new menuList();
            YunohThree.kilogram = 15-20;
            YunohThree.liter = 9000;
            YunohThree.scoop_of_powdered_detergent = 9;
            YunohThree.time = 3;

            menuList YunohFour = new menuList();
            YunohFour.kilogram = 21-25;
            YunohFour.liter = 12000;
            YunohFour.scoop_of_powdered_detergent = 12;
            YunohFour.time = 4;

            Console.WriteLine(YunohOne.purchase);
            Console.WriteLine(YunohTwo.purchase);
            Console.WriteLine(YunohThree.purchase);
            Console.WriteLine(YunohFour.purchase);
        }
    }
}
