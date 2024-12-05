string input;

input = Console.ReadLine();

if (input == "hello")

{ Console.WriteLine("Hello User! Thanks for using this operating system!");tring input;
input = Console.ReadLine();

if (input == "hello")

{ Console.WriteLine("Hello User! Thanks for using this operating system!"); }

if (input == "about")

{ Console.WriteLine("COSMOS OS 1.0 ");Console.WriteLine("hello - Simple OS command");

Console.WriteLine("about - Know about OS ");string input;
input = Console.ReadLine();

if (input == "hello") { Console.WriteLine("Hello User! Thanks for using this operating system!"); }

if (input == "about") { Console.WriteLine("COSMOS OS 1.0 ");

}

if (input == "help") { Console.WriteLine("hello - Simple OS command"); Console.WriteLine("about - Know about OS "); }

if (input == "shutdown") { Cosmos.Sys.Deboot.ShutDown(); }

if (input == "restart") { Cosmos.Sys.Deboot.Reboot(); }while (true)
{

string command = Console.ReadLine();

switch (command) {

case "shutdown": { Cosmos.Sys.Deboot.ShutDown();

break;

}

case "help":

{

Console.WriteLine("hello - Simple OS command");

Console.WriteLine("about - Know about OS ");

break;

}

case "about":

{

Console.WriteLine("COSMOS OS 1.0 ");

break;

}

case "reboot": {

Cosmos.Sys.Deboot.Reboot();

break;

}

case "hello": {

Console.WriteLine("Hello User! Thanks for using this operating system!");

break;

}

default: { Console.WriteLine("No such command");

command = null; break; } }
