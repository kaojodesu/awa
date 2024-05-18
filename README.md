#include <fstream>
#include <stdlib.h>
#include <new>
#include <istream>
#include <sstream>
#include <iostream>
#include <string>
#include <cstring>
#include <exception>
#include <fstream>
#include <iomanip>
#include <vector>
#include <cstdlib>
#include <stdexcept>
#include <csignal>
#include <pthread.h>
#include <unistd.h>
#include <typeinfo>
#include <bits/stdc++.h>
#include <ios>
#include <limits>
#include <stdio.h>
#include <math.h>
#include <cmath>
#include <array>
#include <string.h>
#include <regex>

using std::iterator;
using std::reverse;
using std::setw;
using std::endl;
using std::string;
using std::vector;
using std::cin;
using std::cout;
using std::exception;
using std::out_of_range;
using std::cerr;
using std::istringstream;
using std::clog;
using std::stringstream;
using std::nullptr_t;
using std::setprecision;
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//Preprocessors
#define SS " "
#define LUWAG(i,j) (((i)<(j)) ? i : j )
#define LNY "\n"
#define SPC " "
#ifdef DEBUG
std::cerr << "Boang talaga: " << q << "\n";
#endif  //DEBUG
//
#if 0

#endif

#define CRAIG(a)#a

#define SAD(e,r) e##r

#define DSAAD (as,ah,ag) as##ah##ag

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
int sasasa;
int *sasaas = new int ;
int c = 21 ;

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

template <class TT>
class Stack {
   private:
      std::vector<TT> elems;    // elements

   public:
      void push(TT const& );  // push element
      void pop();               // pop element
      TT top() const;            // return top element

      bool empty() const {      // return true if empty.
         return elems.empty();
      }
};

template <class TT>
void Stack<TT>::push (TT const& elem)
{
    elems.push_back(elem);
}

template <class TT>
void Stack<TT>::pop () {
   if (elems.empty()) {
      throw std::out_of_range("Stack<>::pop(): empty stack");
   }
   // remove last element
   elems.pop_back();
}

template <class TT>
TT Stack<TT>::top () const {
   if (elems.empty()) {
      throw std::out_of_range("Stack<>::top(): empty stack");
   }
   // return copy of last element
   return elems.back();
}

void paraSaIntMain()
{
    try
    {
        Stack <int>             StackInt;
        Stack <std::string>     StackString;

        StackInt.push(12);
        std::cout << "Ge\t" << StackInt.top() << "\n";

        StackString.push("Ay haha\t\n");
        std::cout << "Ge\t" << StackString.top() << "\n";
        StackString.pop();
        StackString.pop();

    }
    catch(std::exception const& ex)
    {
        std::cerr << "Exception\t" << ex.what() << "\t\n";
    }
    std::string newlineBe = "\n" ;

    for(int i = 0;i<10;i++)
    {
            std::cout << newlineBe ;

    }

    int x = 12;
    int *s;
    s = &x ;
    std::cout << s << "\n" ;
    std::cout << *s ;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
class OverWorld
{
   public:

   struct MyException : public std::exception
{
   const char * what () const throw ()
   {
      return "C++ Exception";
   }
};

    long long int lang;
    int* n = new int [lang];
    int* mem = new  int;
    int gold[3] ={12,23,34}  , dami = 3;
    int *haha;
    int bilang = 20;
    int awanKoLods = 123 ;
    int *ipAddress;
    double* pvalue = NULL ;
    float*  wvalue = NULL ;
    const int araySakit = 0 , araySugat = 0 ;
    short int asdasd;
    unsigned int dfasf;
    unsigned short int asfhfd;
    unsigned int asdfsaghfw;
    unsigned long int sadgfdfgj;
    unsigned long long int asdsadrwawfas;
    long double asdsadhe;
    float asdfdsg;
    unsigned char sdasg;
    signed char sadsaf;
    wchar_t sdasd;

    char data[100];

    enum class Difficulty {};

    typedef struct
    {
        int weight ;
        int limit  ;
    }
    Trip;

    struct PointSAS
    {
        int sader, sadest;
    };

    typedef union
    {
        int dasdas,sadsad;
    }
    SelfMade;

    enum year {jan,feb,mar,apr,may,jun,jul,aug,sep,oct,nov,dec};

    typedef unsigned char BYTE;

};
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
class   Box                :    public OverWorld
{
    public:
        Box()
        {
            std::cout << "Constructor Called" << "\n" ;
        }
       ~Box()
        {
            std::cout << "Destructor Called" << "\n";
        }

};
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
template <typename AA>
inline AA const& dddd(const&  a, const& e)
{
    return  a > e ? e : a;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
class   OverWorldSecondo   :    public OverWorld
{
    public:
        void    pointersParaSaStructuresT(Trip *trip);
        void    pointersParaSaStructuresP(PointSAS *sadersss);
        void    paraSaStructure();
        void    paraSaUnion();
        void    enumIto();
        void    typedefIto();
        void    exceptionsIto();
        void    paraSaArray();
        void    mainBagang();
        void    tryThrowCatchPagibigKo();
        void    exitGetOut(int pasok);
        void    defineNewFunctionsDaw();
        void    cjDefNewFunc();
        void    paraSaIntMain();
        void    fileStreamPractice();
        void    pointerPractice();
        void    dynamicMemoryPractice();
        void    objectAllocMem();
        void    paraSaNamespace();
        void    paraSaNestedNamespace();
        void    signalHandling();
        void    threadsPractice();
        int     totalIto(int gold[],int dami);
        int     largestIto(int gold[]);
        int     sum(int k);
        int     maxx(int x,int y);
        double  division(int a, int b);

};
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   pointersParaSaStructuresT(Trip *trip)
{
    std::cout << "\n naito na ang struct pointers mo:\t" << trip->limit ;
    std::cout << "\n naito na ang struct pointers mo:\t" << trip->weight;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   pointersParaSaStructuresP(PointSAS *sadersss)
{
    std::cout << "\n naito na ang struct pointers mo:\t" << sadersss->sader;
    std::cout << "\n naito na ang struct pointers mo:\t" << sadersss->sadest;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   paraSaStructure()
{

    Trip trip1 , trip2 ;

    trip1.limit  = 12 ;
    trip1.weight = 12 ;
    trip2.limit  = 12 ;
    trip2.weight = 12 ;

    pointersParaSaStructuresT( &trip1 );

    struct  PointSAS point1[2], point2[2] ;

    point1[0].sader   = 1 ;
    point1[1].sadest  = 6 ;
    point2[0].sader   = 8 ;
    point2[1].sadest  = 3 ;

    pointersParaSaStructuresP(&point1[0]);
    pointersParaSaStructuresP(&point2[0]);

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   paraSaUnion()
{
    SelfMade SM, SF;

    SM.sadsad = 5 ;
    SM.dasdas = 2 ;
    SF.sadsad = 6 ;
    SF.dasdas = 9 ;

    std::cout << "\n Geto : " << SM.sadsad << SM.dasdas << SF.sadsad << SM.dasdas << "\n" ;

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   enumIto()
{
    enum year month;

    month = jan;

    std::cout << "\nMonth : " << month << "\n" ;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   typedefIto()
{
    BYTE    b1 , b2 ;
    b1   = 'Y' ;
    std::cout << "Type definition mo: " << b1 << "\n";
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   exceptionsIto()
{
    try
    {
        int age = 25;

        if(age >= 26)
        {
            std::cout << "You are old\n";
        }
        else
        {
            throw 1010011;
        }
    }

    catch(...)
    {
        std::cout << "You are not old" << "\n" ;

    }
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   paraSaArray()
{
    std::cin >> lang;
    for (int i = 0; i < lang ; i++ )
    {
        n[i] =  i + 100;
    }
    std::cout << "Element" << setw(13) << " Value\n";

    for (int j = 0; j < lang; j++)
    {
    std::cout <<  j+1 << setw(13) << n[j] << " Value\n";
    }
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
int     OverWorldSecondo   ::   largestIto(int gold[])
{
     int largest = gold[dami];
     for(int i = 0; i < dami ; i++ )
     {
         if (gold[i] > largest )
         {
             largest = gold[i];
         }
     }
     return largest;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
int     OverWorldSecondo   ::   totalIto(int gold[],int dami)
{
    int total = 0 ;

    for (int i = 0; i < dami; i++)
    {
        total += gold[i];
    }

    return total;

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
double  OverWorldSecondo   ::   division(int a, int b)
{
    if(b==0)
    {
        throw "\nboang\tka\tlods\n";
    }
    return a/b;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   mainBagang()
{
   int x = 50 , y = 0 ;
   double z = 0;

   try
   {
      z = division(x, y);
      std::cout << z << "\n" ;
   } catch ( const char* iba)
   {
      std::cerr << iba << "\n" ;
   }
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   tryThrowCatchPagibigKo()
{
    try
    {
        int age = 12;
        if(age <= 18)
        {
        std::cout << "\n Pasado Ka\n";
        }
        else
        {
           throw 1101010101010;
        }
    }

    catch(...)
    {
        std::cout << "\n Uwi sa inyo\n";
    }
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   exitGetOut(int pasok)
{
    exit(1);exit(1);exit(0);exit(1);exit(0);exit(1);exit(0);exit(0);
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   cjDefNewFunc()
{
   try
   {
   throw MyException();
   }
   catch(MyException& e)
   {
      std::cout << "MyException caught" << "\n" ;
      std::cout << e.what() << "\n" ;
   }
   catch(std::exception& e)
   {
      //Other errors
   }
}
///////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   fileStreamPractice()
{

    std::ofstream outfile;
    outfile.open("afile.dat");
    std::cin.getline(data,100);
    outfile << data;
    std::cin >> data;
    std::cin.ignore();
    outfile << data;
    outfile.close();

    std::ifstream infile;
    infile.open("afile.dat");
    infile >> data;
    std::cout << data;
    infile >> data;
    std::cout << data;
    infile.close();

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   pointerPractice()
{

    ipAddress = &bilang;

    std::cout <<  bilang     ;
    std::cout << *ipAddress  ;
    std::cout <<  ipAddress  ;

    int ttt;
    int *sss;
    sss =&ttt;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   dynamicMemoryPractice()
{

    pvalue = new double;
    wvalue = new float[araySakit];

    *pvalue = 121.23;

    delete mem;
    delete pvalue;
    delete []wvalue;

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   objectAllocMem()
{

    Box*    myBoxArray = new Box[4];
    delete []  myBoxArray;

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    signalHandler(int signum)
{
    std::cout << "Interrupted signal  ("<<signum<<")  detected\n" ;

    exit(signum);
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   signalHandling()
{
    int i = 0;

    signal(SIGINT,signalHandler);

    while(i++)
    {
        std::cout << "Going to sleep..............\n" ;
        if(i==3)
        {
            raise(SIGINT);
        }
        sleep(1);
    }
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
int     OverWorldSecondo   ::   sum(int k)
{
   if(k > 0)
   {
       k + sum(k - 1);
       return k;
   }
   else
   {
       return 0;
   }
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
namespace Unang_Pagmamahalan
{
    void BaliwSayos(void BaliwSayos(),void Voang())
    {

    }
    namespace Kabilang_Sanga
    {
        void BaliwSayos(void BaliwSayos(void Baliw()))
        {

        }
        namespace Secret_Sanhi
        {
            void BaliwSayos(void BaliwSayos())
            {

            }
            namespace Pinagbabawal_Malaman
            {
                void BaliwSayo(void mayCrazy())
                {
                    std::cout << "Gaha Valiw \n";
                }
                void BaliwSayo()
                {

                }
            }
        }
    }

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
using namespace Unang_Pagmamahalan::Kabilang_Sanga ::Secret_Sanhi ::Pinagbabawal_Malaman ;
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   paraSaNestedNamespace()
{
    BaliwSayo();
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
namespace Loyal_Ako
{
    void JokeLangHahaha()
    {
        std::cout << "Loyal ako sa lahat \n";
    }
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
using namespace Loyal_Ako;
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   paraSaNamespace()
{
    JokeLangHahaha();

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    OverWorldSecondo   ::   paraSaIntMain()
{

    signalHandling();
    exceptionsIto();
    paraSaArray();
    largestIto(gold);
    totalIto(gold,dami);
    mainBagang();
    paraSaStructure();
    tryThrowCatchPagibigKo();
    cjDefNewFunc();
    fileStreamPractice();
    pointerPractice();
    dynamicMemoryPractice();
    objectAllocMem();
    paraSaNestedNamespace();
    paraSaNamespace();
    sum(awanKoLods);
    exitGetOut(1);


}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
template <typename T>
        inline T const& hax(T const& a, T const& b)
        {
            return a < b ? b : a;
        }

void    templatesPractice()
{
    int           f1 =   123   ;
    int           f2 =   421   ;
    double        j1 =  54.12  ;
    double        j2 =  23.23  ;
    std::string   h1 = "boang" ;
    std::string   h2 = "crazy" ;

    std::cout << hax(f1,f2) << "\n" ;
    std::cout << hax(j1,j2) << "\n" ;
    std::cout << hax(h1,h2) << "\n" ;


}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void preDefinedPreprocess()
{
    std::cout <<  __LINE__  << "\t" << __TIME__ << "\t" << __DATE__ << "\t" << __FILE__ << __FILE__<< __DATE__<< __TIME__ << __LINE__ << "\n" ;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void vava(int q)
{

}
template <typename lolo>
inline lolo const& saff(const& m, const& n)
{
    return m > n ? n : m;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void printtt( long long int f )
{
    std::cout << "\nNaito ang: " << f;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void printss()
{
    printtt(CHAR_MIN);
    printtt(CHAR_MIN);
    printtt(CHAR_MIN);
    printtt(CHAR_MAX);
    printtt(CHAR_MAX);
    printtt(SCHAR_MAX);
    printtt(SCHAR_MAX);
    printtt(UCHAR_MAX);
    printtt(UCHAR_MAX);
    printtt(UCHAR_MAX);
    printtt(UINT_MAX);
    printtt(UINT_MAX);
    printtt(INT_MAX);
    printtt(INT_MIN);
    printtt(INT_MIN);
    printtt(INT_MAX);
    printtt(CHAR_BIT);
    printtt(LONG_MAX);
    printtt(ULONG_MAX);
    printtt(LONG_MIN);
    printtt(SHRT_MAX);
    printtt(SHRT_MIN);
    printtt(USHRT_MAX);
    printtt(LLONG_MAX);
    printtt(LLONG_MIN);
    printtt(ULLONG_MAX);
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
int maxx(short int x,short int y)
{
    if(x == 1)
        long unsigned int xxx = x;
    if(x > y)
        return x ;
    else
        return y ;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void conversionIto()
{
    int sadsaddd = 0;
    char sdsadasdasd = 'A';
    int asd = sadsaddd + sdsadasdasd;
    float dsssds = asd + 1.43 ;

    double ssss = 2.2;

    int dds = (int)ssss + 3;

    int sadasd = static_cast<int>(dsssds);
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void    cast()
{
    int numss = 235 ;

    double douasd = static_cast<int>(numss);

    std::cout << "DT: " << typeid(numss).name() << "\n" ;

    std::cout << "TC" << typeid(static_cast<double>(numss)).name() << "\n";

    std::cout << "DT" << typeid(douasd).name()  << "\n" ;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//To illustrate the dynamic cast modifier
class Animal
{
protected:
    virtual void asd() const
    {

    }
    virtual void speak() const
    {
        std::cout << "Hayop! " << "\n" ;
    }
};

class Dog : public Animal
{
public:
    void speak() const override
    {
        std::cout << "Aw Aw! " << "\n" ;
    }
};

class Cat : public Animal
{
public:
    void speak() const override
    {
        std::cout << "Nya Nya!? " << "\n" ;
    }
};

void sssIntMain()
{
    //base class pointer
    Animal* anmlPtr  = new Dog() ;
    Animal* anamlPtr = new Cat() ;
    //down casting
    Dog* dogPtr = dynamic_cast<Dog*>(anmlPtr);
    if(dogPtr)
    {
        dogPtr->speak();
    }
    else
        std::cout << "Dog not " << "\n" ;

    Cat* catPtr = dynamic_cast<Cat*>(anamlPtr);
    if(catPtr)
    {
        catPtr->speak();
    }
    else
        std::cout << "Cat not" << "\n" ;

        delete anmlPtr;
        delete anamlPtr;

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void constModifier()
{
    //gets ko na :)
    const int  nummmm = 123 ;
    const int *sxxs = &nummmm;

    //Always use this casting operator for constant
    int *nonConstPtr = const_cast<int*>(sxxs);
    std::cout << "Modified : " << nonConstPtr ;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void reinterpretCastModifier()
{
    int   xxxs = 21 ;
    int*  numberPointer = &xxxs;
    char* charPointer = reinterpret_cast<char*>(numberPointer);

    std::cout << reinterpret_cast<void*>(charPointer) << "\t\n" ;

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void operators()
{
    short int c1 , c2 , c3 , c4 , c5 , c6 , a = 37, b = 34 ;
    c1 = (a |  b);
    c2 =  ~(a);
    c3 = (a &  b);
    c4 = (a ^  b);
    c5 = (a >> b);
    c6 = (a << b);
    std::cout << "eto oh "  << " \n" ;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void sizeoof()
{
    int asmr = 432 , dslr = 312 ;
    int     *as = new int(123);
    double  *ds = new double(12.32);
    char    *xc = new char('S');

    std::cout << sizeof(as) << "\n" ;
    std::cout << sizeof(*as) << "\n" ;
    std::cout << sizeof(*ds) << "\n" ;
    std::cout << sizeof(ds) << "\n" ;
    std::cout << sizeof(xc) << "\n" ;
    std::cout << sizeof(*xc) << "\n" ;

    std::cout << sizeof(asmr * sizeof(dslr) ) << "\n" ;

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
struct dsss
{

}dssss;
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
union ssdsad
{

}huh;
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

class asd
{
public:
    static int asddas, asdasddd;
    private:
    static int saddsadsa , asddsa;
};
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//namespace ito
std::string lkk = "sadfds" ;
std::string kll = "asfdf" ;
class Developer
{
public:

   std::string  Lkk = "sad" ;
   std::string  Kll = "asd" ;
    Developer(std::string Lkk , std::string Kll):Lkk(lkk),Kll(kll){}
};
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void cinLahatIto()
{
    using namespace std;

    char x[432];

    std::cin.getline(x,5);

    std::cin.getline(x,2365);

    std::cin.read(x,32);

    std::cin.get(x,3);

    std::cin.ignore(numeric_limits<streamsize>::max(),'\n');

    std::cin.getline(x,321);
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void coutLahatIto()
{
    char sadsdsdfa[] = { 's' , 'a' , 'h' , 'l' , 'r' , 'c' , 'h' , 'h' , 'e' } ;
    char ch = 'f' ;
    std::cout.write(sadsdsdfa,5);
    std::cout.put(ch);
    std::cout.precision(ch);
    std::cout << sadsdsdfa << '\n' ;
}
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
enum class Choice{};
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//function pointers/reference
//function reference
void dd(int* kj)
{
    *kj = 123 ;
}
void ddda(int* asd)
{
    *asd = 1233;
}
void labasLods()
{
    int whatsup  = 314, gagaga = 213;
    dd(&whatsup);
    dd(&whatsup);
}
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//function natutunan ko sa geeksforgeeks
class CCCC
{
public:
    static  int sum(  int x,  int w)
    {
        return x+w;
    }
    static  double sum( double x,  double w)
    {
        return x+w;
    }
    double sda(double as)
    {
        return as*as*as;
    }
    static double sum(double x, double w, double y)
    {
        return x+w+y;
    }
};

void aba(void)
{
    CCCC cpp;
    cpp.sum(8745123,457347);
    cpp.sum(321.1,123.1);
}
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//loops

#define CB  '{'
#define CBC '}'
#define SP  "\t"
#define SECRETBAYAEE "\b"
#define COMM " , "

void printLoops(int i)
{
    std::cout << i << "\n" ;
}

void loopsIto()
{
    int arr [] = {1,2,3,4,5,6,7,8,9};
    long unsigned int asdas = 5 ;
    for( int& element: arr )
    {
        std::cout << element << "\t";
    }

    std::vector<long int> arrayys = {12,3213,2134,243,4534,3124,535,32,32};

    std::vector<long int> asdd = {154,24,376,323,74,125,651,2312,356,22};
    for( auto& as : asdd)
    {
        std::cout << as << "\n" ;
    }

    for_each( arrayys.begin() , arrayys.end() , printLoops );

    for(int x , xx , xxx ; x <= asdas , xx <= asdas , xxx <= asdas  ; x++ , xx++ , xxx++  )
    {
        std::cout << LNY << x << SP << xx << SP << xxx << SP ;
    }

    for (auto sssa: asdd)
    {
     std::cout << LNY << sssa ;
    }

    for (auto asdal:{123,534,123,654,123,754,23,56,234,67,43} )
    {
        std::cout << LNY << asdal;
    }

    for(int ls : {1,2,3,5,2} )
        {
            std::cout << LNY << ls ;
        }

    std::string strs = "ASA" ;
    for (char sa : strs )
    {
        std::cout << LNY << sa ;
    }

    std::map<long long unsigned int,long long unsigned int > MP( {{123,412},{423,513,},{876,263}} );
    for(auto naeto : MP)

        std::cout << CB << naeto.first << COMM << naeto.second << CBC << LNY ;

    for_each(asdd.begin(),asdd.end(),printLoops);
}

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//nested class
class Labas
{
public:
    class Loob
    {
    public:

        static int sadsd;
        static long unsigned int sads;

    };
};
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
int asd::asdasddd = 23;
int asd::asddas =11;

int Labas :: Loob :: sadsd = 143 ;
long unsigned int Labas :: Loob :: sads = 213 ;

#define NL "\n"

void asdkkkkk()
{
    std::istringstream str(" Programmer ");
    std::string line;
    getline( str >> std::ws, line );
    std::cout << line ;
    std::cout << "just a line" << std::flush ;
    std::cout << "\n123" << std::ends;

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
long int ccc = 123213;

void switchStatement()
{
    switch (::ccc)
    {

    default:

        std::cout << "Boang \n" ;
        break;

    case 1 :

        std:cout << "asdasd\n" ;
        break;

    case 2 :

        std::cout<< "asdasdasd\n";

        switch (c)
        {

        default:

            std::cout<< "\nasdsa\n" ;
            break;

        case 1 :

            std::cout << "Naito na oh" << c << "\n" ;
            break;
        }
    }
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
void kahaponPangPractice()
{
    int c = 0 , a = 213 , b = 5 ;
    c = a & 3;

    std::cout << ::c << '\n' ;
    std::cout << c << LNY ;
    Developer sadf = Developer("dasdsa","sdfasd");
    std::cout << sadf.Kll << SPC << sadf.Lkk << LNY ;
    Labas asdsaSasas;
    Labas :: Loob dasSaa;
    asd::asdasddd = 123;
    std::cout << std::setfill('^') ;
    std::cout << std::setw(231) << ::ccc << std::setw(23)  ;
    std::cout << std::setbase(16) << ::ccc ;
    printf("sadasdsadsasd",::ccc);
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//user-defined function modifiers ata
void fi(string s,int xls)
{
    s = "asdasdasd";
    xls = 123;
}

void isaPa()
{
    string s = "asd" ;
    int xls = 1232 ;
    fi(s,xls);
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//angas at nakakatawa din naman itong function hehe
//dami kong natutunan sa default parameters ng functions
//medyo comprehensive intindihin ang inline functions pero gets ko na
//at dapat ay careful kang gumamit ng inline functions
class Largest
{
    int a,b,m,var;

    public:

        void well_haha();

        friend void set_data();
        friend void find_max(Largest);

        Largest(int xxx = 0): var(xxx){} ;

        void setVar(int xxx)
        {
            var = xxx;
            return ;
        }
        int getVar()
        {
            return var;
        }
        void helloLods();
        void angLoko();
        long int well(long int why);

        friend long double fe(long double he);

};

inline long int Largest::well(long int why)
{
    return why*why*why*why;
}

long double fe(long double he)
{
    return he-he-he-he-he ;
}

inline void Largest::helloLods()
{

}
inline void Largest::angLoko()
{

}
inline void Largest::well_haha()
{

}
void set_data()
{

}
void find_max(Largest t)
{
    if(t.a>t.b)
    t.m = t.a;
    else
    t.m = t.b;

    std::cout << "\nLargest number is:\t" << t.m ;
}
void miniIntMain(Largest l, Largest *LLL = new Largest(123) )
{
    l.well_haha();
    set_data();
    find_max(l);
    Largest ll(123);
    ll.setVar(1233);
    std::cout << "\nTemporary Importance of this algorithm\t" << ll.getVar() ;
    LLL->setVar(1232);
    std::cout << "\nTechnical Maintainance is now on-hold\t" << LLL->getVar() ;
}

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
int sum(int q = 0 , int w = 0, int e = 0 , int r = 0 , int t = 0 , int y = 0 , int u = 0 , int i = 0 )
{
    return  (q+w+e+r+t+y+u+i) ;
}
void upjl(int q = 123 , int w = 234 , int e = 645 , int r = 678 , int t = 678 , int y = 543 , int u = 213 , int i = 867 )
{
    sum(y);
    sum(q,y);
    sum(q,y,u);
    sum(q,y,e,w);
    sum(q,y,r,e,w);
    sum(q,y,u,w,e,r);
    sum(q,u,i,y,w,t,r,e);
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
inline int prod(int x = 213 , int y = 132 , int w = 543)
{
    return x*y*w;
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//Lambda expression
//nakakatuwa din gamitin
//nakakatuwa talaga gamitin haha
void printVector(vector<int> v)
{
    // lambda expression to print vector
    for_each(v.begin(), v.end(),[] (int i){std::cout << i << " ";});
    std::cout << LNY ;
}
void bagongIntMain( std::vector<int> vv = {123,432,123,354,123,15,123,145,12,31,4,134,12,41,24,98})
{
    std::vector <int> :: iterator p = std::find_if(vv.begin(),vv.end(),[] (int i){return i > 4;} );

    std::sort( vv.begin() , vv.end() , [](const int &a,const int &b) -> bool {return a > b ;} );

    std::vector<int>   :: iterator x = std::find_if(vv.begin() ,vv.end() ,[](int i) {return i > 5;} );

    int giveFive = std::count_if(vv.begin(),vv.end(),[](int i){return (i > 5); });

    p = std::unique( vv.begin() , vv.end() , [](int a,int b) {return a == b;}  );

    vv.resize(distance(vv.begin(),p));

    int aray[] = {987,123,12,312,123,65,78,98,967,4,56,458,345,86,};

    int f = std::accumulate( aray , aray + 10 , 1 , [](int i, int j){return printf("\nFactorial of 5 is: ",i * j,LNY );} );

    auto square = [](int i)
    {
        return i * i;
    };

    std::vector<int>::iterator s = std::find_if(vv.begin() ,vv.end() , [](int sssw){return sssw+LNY;} );

    std::sort(vv.begin(),vv.end(),[](const int &a, const int &b)-> bool{return a > b ;} );

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//Lambda expression with enclosing scope is formally fun in a professional way haha
//Just use signs or significant variables for your Lambda expression functions
//Lambda expression function is pretty good and flexible though
void nanamanEhEh( short int whatts = 97 ,std::vector<int> kkk = {876,231,654,234,786,234,456}, std::vector<int> www = {65,123,678,345,879,345,786,745,66,9,45,56,6} )
{
    auto pushInto = [&](int m)
    {
        kkk.push_back(m);
        www.push_back(m);
    };

    auto sadsa = [&](int sa)
    {
      kkk.push_back(sa);
      www.push_back(sa);
    };

    pushInto(2734);

    [kkk]()
    {
     for(auto p = kkk.begin() ; p != kkk.end() ; p++ )
     {
         std::cout << LNY << *p << LNY ;
     }
    };

    std::vector<int>::iterator p = std::find_if( kkk.begin() , kkk.end() , [whatts](int i){ return i > whatts ;});

    int count_N = std::count_if( kkk.begin() , kkk.end()  ,[=](int a){return (a >= whatts ); });

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//Pointers na tayo everyone
//what pwede pala yun according to syntax pero in logic, error yan ata
//nani pwedeng pwede mong gawing pointer ang functions kakatuwa
//kakatuwa din void pointers function parang kasing dali ng templates
//wow pinagaralan pa muna ang Dangling,Void,Null,Wild
#define AY 4212

template <class www>
inline www add(www x,www u ){return x+u;}

int* createArrrr(int x)
{
    static int* arrrr = (int*)(malloc(x * sizeof(int)) );
    return arrrr;
}

void anoDaw(int crt,int *sqrr,float *sqrrt)
{
    cbrt(crt);
    sqrt(crt);
}

int* dangling()
{
    static int x = 12;
    return &x;
}

void increase(void* aw,int sizee)
{
    if(sizee==sizeof(char))
    {
       char* s;
       s = (char*)aw;
       (*s)++;
    }

    else if(sizee==sizeof(int))
    {
        int* w;
        w = (int*)aw;
        (*w)++;
    }
}
template <typename T>
T jiji(T* wow )
{
    *wow * *wow;
}

void intNaBago(int result = 0 , int xnb = 123, int awan = 123, double ew = 31.344 , double results = 0.0 )
{
    jiji(&awan);
    int* walaNa = NULL;

    int* hahhh;
    {
        int sassss = 123;
        hahhh = &sassss;
    }

    int* xx = dangling();

    fflush(stdin);

    int* ja = createArrrr(xnb);

    int* sssa = (int*)(malloc( sizeof(int)) );

    free(sssa);

    sssa = NULL ;

    int(*add_ptr)(int,int) = &add;

    int(*secret_ptr)( int , int ) = &add;

    double(*doub_ptr)(double,double)=&add;

    results = doub_ptr(ew,ew);

    result = add_ptr(xnb,awan);

    printf("The sum:",SS,result,LNY);

    int whattt[] = {123,123,213,123,23};

    int *awann = &xnb;
        *awann = 213;

        int *s = &xnb;

        int *sua = &xnb;

        int **secretNa = &awann;
            **secretNa = 2133;
            **secretNa = 23;

            int *why ;
            int *cra ;
            cra = whattt;
            why = whattt ;

            for (int i = 0 ; i < 5 ; i++)
            {
                printf(LNY,cra,LNY,*cra);
                cra++;
            }

            for(auto& w: whattt)
            {
                std::cout  << LNY << w  ;
            }

            for (int i = 0; i < 5 ; i++)
            {
                std::cout << LNY << why[i] ;
            }

    char ptr[] = {'a','w','j','v','i','h'};
    char x = *(ptr+4);
    char y = ptr[3];

    char   q = 122;
    char  *w = &q ;
    char **e = &w ;

    std::nullptr_t  wxyz;

    if(xnb > 1 && awan < AY)
    return intNaBago(xnb - 1, awan * 2 );

    increase(&xnb,sizeof(int));

    int   loloMo = 213 ;
    float iyT = 123.43 ;

    void* yummy;
    yummy = &loloMo;
    printf( "sadasd\t" ,((int*)yummy));
    yummy = &iyT;
    printf("asd\t",((float*)yummy));

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//pointers ito ulit my friends
void asddPtr(std::nullptr_t  asdssss,std::nullptr_t  asddiuy)
{
    int *sad = nullptr;
    std::nullptr_t  ptrIsa , ptrDalawa;
    if(sad)
    {
        std::cout<<LNY<< "TRUE" ;
        if(ptrIsa>=ptrDalawa)
        {
            if(ptrIsa==nullptr)
            {

            }
            else
            {

            }
        }
        else
            {

            }
    }
    else
        {
            std::cout<<LNY<< "FALSE";
        }

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
// pointers na tayo everyone ulit haha how many years have we been for a long time

inline void asdasd(int& x , int& w, int temp = 0 )
{
    temp = x;
    x = w;
    w = temp;
}
void panaloSiReymar(int sads = 213,int sdsa = 213)
{
    asdasd(sads,sdsa);
}

struct Studentt
{
    std::string awan;
    std::string sstandard;
    int sa;
};

int& nani()
{
    static int ekss = 234 ;
    return ekss ;
}

void swapcs(char*& weh , char*& hihi )
{
    char*  temp;
    temp = weh ;
    weh  = hihi;
    hihi = temp;
}

struct demo
{
    int a ;
};

void bagongPanimulaNaNaman(const Studentt &C)
{
    int sds = 123 ;
    int &sd = sds ;
    std::cout << LNY << C.awan << LNY << C.sa << LNY << C.sstandard ;

    std::vector <int> ssa{1,23,12,12,3412,512,3,214,21,1};
    for(int& s : ssa)
    {
        s += 5 + ( s / s + ( s * s + ( sqrt( ( s * s ) ) ) ) ) ;
    }
    for(int a : ssa)
    {
        std::cout << LNY << a ;
    }
    std::vector<std::string> as{ "asd  asd asd " , "asdasd s" , " sasdsa" };

    for(const auto& xxx : as)
    {
        std::cout << LNY << xxx;
    }

    int jin     = 213    ;
    void *eks   = &jin   ;
    int &wjat   = jin    ;
    int &jinhoo = wjat   ;
    int &jinbe  = jinhoo ;
    jinbe ++ ;

    nani() = 214 ;

    int *ptr = NULL;
    std::nullptr_t ptrs, prs;
    int& reff = *ptr;
    int& jimbe = reff;

    char* ui   = "sige ba sige ba";
    char* boil = "bakit ako nalang";
    swapcs(ui,boil);
    int *ok = &jin ;
    int &ojt = *ok ;
    int **momo = &ok;
    int ***koko= &momo;
    int ****nono= &koko;

    demo d;
    demo *poly = &d;
    demo &polym=  d;

    poly->a=213;
    polym.a=123;

    std::cout << LNY << "point\t" << poly->a << LNY << "ref\t"  << polym.a ;

}

void geee(std::vector <int> ss = {123,213,123,123,123,213}, std::vector <std::string> funn = { "juju" , "gym" , "jinhwoo" },int momohi = 978, int mimi = 98 )
{
    for(int& sss : ss)
    {
        sss+=sss;
    }
    for(int sss : ss)
    {
        std::cout << LNY << sss ;
    }
    for(const auto& xx : funn)
    {
        std::cout << LNY << xx ;
    }

    int *bP;
    bP = &momohi;
    bP = &mimi;
    }

struct Kok
{
    int    ba;
    string ho;
    char   mo[60] ;
};
printItoo(const struct Kok* kiki )
{
    printf("What the: %s\n ", kiki->ba );
    printf("What the: %s\n ", kiki->ho );
    printf("What the: %s\n ", kiki->mo );

}
void kokoko()
{
    struct Kok h;

    strcpy(h.mo,"dasddas123$#$%^&#!L>?");
    printItoo(&h);
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//ganito pala ang polymorphism with structs nakakainteresado akala ko ay classs objects lang meron nito
struct jong
{
    void(*mun)();
};

void kokk(){printf("\nnaprint na");}

void goo( struct jong* jon ){ jon -> mun = kokk; }

struct song
{
    struct jong woo;
};

void lili(){printf("\ngrazy" );}

void lolo(struct song* son)
{
    goo(&(son->woo));
    son->woo.mun = lili ;
}

void pipo( const struct jong* woo){ woo->mun(); }

void binhiKo( struct jong j , struct song s )
{
    goo(&j);
    lolo(&s);

    pipo(&j);
    pipo((struct jong*)&s);

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//pointer functions that returns multiple value
void jojojojo(
              int x , int y , int* summ = 0, int* proo = 0 ,
              std::string w = "dsa" , std::vector <std::string> jou = { "joo" , "jou" , "jpeg" }
              )
{*summ = x + y ;*proo = x * y;}

void itoOh(int x = 213, int w = 987, int summ = 0, int proo = 0, std::string y = "joooi", std::vector <std::string>  pui = { "ty" , "jgh" , "das" } )
{
    jojojojo(x,w,&summ,&proo,y);
}

//pointers para sa memory allocation hehe

void momo( int **da )
{
    *da = (int*)std::malloc(sizeof(int) );
    if(*da!=NULL)
    {
        **da = 241;
    }
}

void joji(int* bamo = 0)
{
    momo(&bamo);
    printf( LNY ,"Dynamic value set is: %d" , *bamo );
    free(bamo);

}
void initialize(int* arr,int siz)
{
    for(int  i = 0 ; i != siz ; i++ )
    {
        arr[i]=i++;
    }
}

void alaamKo(void* syaAngSagot[213],int siz = 1234 )
{
    int arrr[siz];
    initialize(arrr,siz);

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//arrays na tayo everyone
using v = void;
using str = std::string;
using Bibo = std::vector<std::string>;
using ca = const char;
using ci = const int;
using cc = char;

v jojij(int* arraa[] )
{
    Bibo Kpop = { "lol" , "sad" , "asd" };
}
void ko(char* sa)
{
    scanf("%d" ,sa);

}
void sol( )
{
    std::string strDawOo("asasdddd");
    std::stringstream jo(strDawOo);
    while(jo >> strDawOo )
    {
        std::cout << LNY << strDawOo ;
    }
    char kpop[]={ 's', ' ' ,'h' ,'w'};
    ko(kpop);

}
namespace X { f(int){}  ;}
namespace W { f(char){} ;}

using namespace X;
using namespace W;
void itoLodsKOLol()
{
    f('a');
    f(214);
}

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//function overloading na tayo guys hehe
v ll(int x,float w){}
v ll(float x, int w){}

v you(ci *x){}
v you(int *x){}
v ito()
{
    int l = 123;
    const int ppp = 32;
    you(&l);
    you(&ppp);
}
v oo(ca *s){}
v oo(cc *s){}
v lofi(cc ss = 'd')
{
    ca *s = "sad" ;
    oo(s);
    oo(&ss);
}

v lll(ci &s){}
v lll(int &s){}
v lokikuji( int eks = 23 , int way = 32 )
{
    lll(eks);
    lll(way);
}

int l(int  w = 232, int k = 213);
v sd()
{
    l();
}
int l(int x ,int s)
{
    return x+s;
}

bool d(){return 1;}

template<typename T>
T bubblesort(T m[], T s )
{
    for(int i = 0; i < s - 1 ; i++ )
    {
        for(int j = i  ; j < s - i ; j++ )
        {
            if(m[j]>m[j+1])
            {
                swap(m[j],m[j+1]);
            }
        }
    }

}

template <typename T>
T selection(T arrr[],T s,T i = 0,T j = 0,T minidx = 0 )
{
    for( i ; i < s - 1 ; i++ )
    {
        minidx = arrr[i];

        for( j = i + 1 ; j < s ; j++ )
        {
            if (arrr[j]<minidx)

                   minidx = arrr[j];

        }

        swap(arrr[i],minidx);
    }
}

template <typename T>
T insertion(T arrr[], T n , T i = 1,  T j = 0 , T key = 0 )
{
    for( i = 1 ; i < n ; i++ )
    {
        key = arrr[i];
        j = i - 1 ;
        while(j >= 0 && arrr[j] > key )
        {
            arrr[j+1] = arrr[j];
            j-- ;
        }
        arrr[j+1] = key;
    }

}

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//medyo related dito ang functions galing sa dicrete math wow
class BaseClass
{
public:
    virtual void Display()
    {
        cout << "\nThis is Display() method"
                " of BaseClass";
    }
    void Show()
    {
        cout << "\nThis is Show() method "
               "of BaseClass";
    }
};

class DerivedClass : public BaseClass
{
public:
    // Overriding method - new working of
    // base class display method
    void Display()
    {
        cout << "\nThis is Display() method"
               " of DerivedClass";
    }
};

v sad(DerivedClass d)
{


}

v sd(DerivedClass dr ){ BaseClass &bs = dr; bs.Display(); dr.Show(); }

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//template na tayo lods master natin like basic
template <class P , class O = cc> class HetoOh
{
    P d;
    O p;
public:

    v LoL(){}

};

#define J  HetoOh

v loveIt( )
{


}

v POPO(int kokoLang = 1)
{
    J<cc>a;
    J<int,double>n;
}

template<class T , int max > T geTo(T arrr[], int n ){return max;}

void Lods(int s = 12,int pl = 434)
{
    int arrry[] = {123,123,123,213,123,213,123,123} ;
    geTo<int,32>(arrry,pl);
}

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//jaja pinatawa ako dun ah hahaha
//another win
//panalo nanaman jajaja

template<class T,class X> T mull(T x = 0 , T z = 0 ) { return x*z ;}

template <class T> T advertisement ( T x = 23, T w  = 23.325)
{ using i = int; using d = double; auto result = mull<i,d>(x,w) ; return result; }

template <class> void advertisement(int a = 21 , int as = 34 ){ std::cout << LNY;}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
v practiceMunaSandali()
{

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//typedef na tayo my friends
#define td typedef

v logicYarn(int o=23,int i=432,int p=324,int w=535,int x=2 )
{
    o = i = w = x = p = 123 ;
    td unsigned long long int ulli;
    td std::vector<int> vi;
    vi layoLods;
    layoLods.push_back(3);
    td int arrrrrr[0] ;
    arrrrrr arayko[32] ;
    ulli {123} ;
    td unsigned char uc;

}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
#define SF sort_heap
v string_na_tayo()
{
    char str[20];

    scanf("%[^\n]s",str);

    char* ptr = str;

    while(*ptr != '\0' )
    {
        printf( "%s" ,*ptr);
        ptr++;
    }
}
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//practice muna tayo sa strings myself
v another_strings_again()
{
    std::string str1 ;
    str1.push_back('s');
    str1.pop_back();
    getline(cin,str1);
    str1 = "Napagtripan pa \n" ;
    std::string strr1 = "lokoloko \n";
    strr1.swap(str1);
    std::string::iterator ts;
    std::string::reverse_iterator ts1;
    str1.resize(11);
    str1.capacity();
    str1.shrink_to_fit();
    str1.capacity();
    for(auto strr2 = strr1.cbegin() ; strr2 != strr1.cend();strr2++)
    {
        std::cout << *strr2 ;
    }
    for(auto strr3 = strr1.crbegin() ; strr3 != strr1.crend() ; strr3++)
    {
        std::cout << *strr3 ;
    }
    std::string strrr("asdasd");
    str1.append(strr1);
    std::cout << str1 + strr1;
    char wal[]="asdasasdas";
    char wala[]=" asdasasdas\n";
    strcat(wal,wala);

    std::string jio("walwal na");
    std::string ko("bawal ko");
    std::string resulta;
    for (int i = 0; jio[i] != '\0' ; i++ )
    {
        resulta += jio[i]  ;
    }
    for(int i = 0; ko[i] != '\0'; i++)
    {
        resulta += ko[i];
    }
    std::string success = resulta;
}
class base
{
    protected:
        virtual string concatenate(string &str1,
                                   string &str2) = 0;
};

// Derive class
class derive: protected base {
    public:
        string concatenate (string &str1,
                            string &str2)
        {
            string temp;
            temp = str1 + str2;
            return temp;
        }
};

class Base {
    public:
      char init[100] = "this is init";
      char add[100] = " added now";

      friend void myfun(Base b);
};

void myfun (Base b)
{
    // Pass parameter to concatenate
    strcat (b.init, b.add);

    cout << b.init;
}

// Driver code
void mainn(Base b)
{
    string init("this is init");
    string add(" added now");

    // Create string object
    derive obj;

    // Print string
    cout << obj.concatenate (init, add);


    myfun(b);

}
v labas()
{

}

v stringssLods()
{
    char *s[4]={ "asd" , "das" , "asd" , "as" };
    char  x[3][10] = { "asd" , "das" , "asd" };
    std::vector <std::string>  w = {"das" , "asd" , "as"} ;
    std::array<std::string,3> j = { "lolo" , "jij" , "gdsf" };
    for(auto &m: s )
    {
        std::cout << m ;
    }
    for(auto &a:x)
    {
        std::cout << a ;
    }

}

v stringsTokenization(std::string line = "asdsadasdas asdasd asdsa", std::vector <std::string> tokens = {},std::string intermidiate = "" )
{
    std::stringstream checkLine(line);

    while(getline (checkLine,intermidiate,' ') )
    {
        tokens.push_back(intermidiate);
    }

    for(int i = 0 ; i  < tokens.size() ;i++)
    {
        std::cout << tokens[i] ;
    }
}

v goodmorningMayBagongTechniqueNaTayo()
{
    char str[] = "dasdasd dasdsad sad" ;

    char* token = std::strtok(str, " " );

    while(token!=NULL)
    {
        printf( "%s\n" ,token);
        token = strtok(NULL," ") ;
    }

    return goodmorningMayBagongTechniqueNaTayo();
}

v bagongTeknikSaStringsNaNaman()
{
    char str[] = "discipline consistency serious";
    char *key = str;
    char *token;
    while( (token = strtok_r(key, " " , &key) ) )
        {
            printf( "%s\n" , token );
        }
     return (bagongTeknikSaStringsNaNaman()) ;
}

std::vector <std::string> tokenize(const std::string str, const std::regex re )
{
    //std::sregex_token_iterator it {str.begin(),str.end(), re , -1};
    //std::vector <std::string> tokenized{ it , {} };

    //tokenized.erase(std::remove_if(tokenized.begin(),tokenized.end(),[](std::string const& s){return s.size() == 0;}),
    //tokenized.end());

    //return tokenized;
}

v intMainStringDaw( )
{
    //const std::string str = "Break a string spaces, commas, and period.";
    //const std::regex re(R"(\s,.()?)");
    //const std::vector<std::string> tokenized = tokenize(str,re);
    //for(auto& token:tokenized){std::cout << "\n" << token ;}
    return intMainStringDaw() ;
}

 v  bagongStringDaw(std::string x = "discipline power = philosophy" )
{
    signed short int b = 0;
    std::string w ;
    w = x.substr(5);
    signed short int p = x.find("=");
    signed short int m = x.find("w");
    std::string f = x.substr(p+1);
    std::string l = x.substr(b,p);


    return (bagongStringDaw()) ;
}

// Returns sum of all substring of num
int sumOfSubstrings(std::string s)
{
    std::vector<int> v;
    int n = s.length();
    for (int i = 0; i < n; i++) {
        for (int len = 1; len <= n - i; len++) {
            std::string sub = (s.substr(i, len));
            int x = stoi(sub);
            v.push_back(x);
        }
    }
    int res = std::accumulate(v.begin(), v.end(), 0);

    return res;
}

int substrings(std::string s,int n)
{
    std::vector<int> v;
    for (int i =i+0;i<n;i++ )
    {
        for(int len = 1 ; len <= n-i ; len++)
        {
            std::string sub = ( s.substr(i,len) );
            int x = stoi(sub);
            v.push_back(x);
        }
    }
    return *max_element(v.begin(),v.end() );
}

int subsstrings(std::string s,int n)
{
    std::vector<int>v;
    for(int i = 0; i < n ; i++)
    {
        for(int len = 1;len <= n-i;len++)
        {
            std::string sub = (s.substr(i,len) );
            int x = stoi(sub);
            v.push_back(x);
        }
    }
    return *min_element(v.begin(),v.end());
}

// Driver code to test above methods
void bbmain()
{
    std::string num = "1234";
    int sizen = num.length();
    std::cout << "\n" << sumOfSubstrings(num) ;
    substrings(num,sizen);
    subsstrings(num,sizen);
    return bbmain();
}

v stringsMyFriends()
{
   const int MAX = 3;
   int  var[MAX] = {10, 100, 200};
   int  *ptr;

   // let us have address of the first element in pointer.
   ptr = var;
   int i = 1;

   while ( ptr < &var[MAX] )
   {
      cout << "Address of var[" << i << "] = ";
      cout << ptr << endl;

      cout << "Value of var[" << i << "] = ";
      cout << *ptr << endl;

      // point to the previous location
      ptr++;
      i++;
   }
//hello pointers na ulit
}
int * pt()
{
    signed short int l=2 ,w=12;
    std::random_device rd;
    std::uniform_int_distribution <signed short int> distance(l,w);
    std::uniform_real_distribution <float> dist(123.435,645.7823);
    signed short int wala = distance(rd) + dist(rd);

}
int * getRandom( )
{
   static int  r[10];

   // set the seed
   srand( (unsigned)time( NULL ) );

   for (int i = 0; i < 10; ++i) {
      r[i] = rand();
      cout << r[i] << endl;
   }
   return r;
}

v helloProfessionals()
{
    int *pp;
    pp = pt();
    int *s;
    s = getRandom();

    int ww = 23,oo=65;
    int *ss = &ww;
    s--;
    s++;
    int& rr = ww;
    rr++;
    rr--;
    int& aa = rr;
    int *qq,*kk;
    kk = &ww; qq = &oo; kk += 3; qq += 3;
    ww = qq - kk;
    *kk = 10;
    *qq = *kk;
     kk = qq ;
    *kk = 20;

    int arrps[12]; int *ar = &arrps[0] ;
    if(qq==ar)
    {
        printf("boang\n");
    }

}

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//pointers na tayo ulit part two
v point(signed short int* arr ,signed short int x ,signed short int w)
{
    return point((signed short int*)arr,x,w);
}
v same(signed short int j = 5,signed short int k = 9)
{
    signed short int arr[][9]= { {5,4} , {9,9} } ;
    point( (signed short int*)arr,j,k );
}

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//nakakainteresado itong method ah pointers to functions sya btw hehe
int nextt(int a ,int n,int (*functocall)(int,int),int x = 0 )
{
    return x = (functocall(a,n) ) ;
}
int add(int j , int k ){return j+k;}
int sub(int j , int k ){return j-k;}
int mul(int j , int k ){return j*k;}

int geng(int s = 12){return s ;}
int oh(int (*s)(int),int secret = 234 ){return s(secret);}

void increasee(void* kuha,int bilang)
{
    if(bilang==sizeof(char) )
    {
        char* x ; x = (char*)kuha; x++;
    }
    else if(bilang==sizeof(int))
    {
        int* w; w = (int*)kuha; w++;
    }
}
bool compare(const int * x, const int * y)
{
    return (*(int*)x == *(int*)y) ;
}

int searchh(int *arrr , int sizee, int element, int *findd, bool compare(const int *,const int *) )
{
    for(int i = 0 ; i < sizee ; i++)
    {
        if(1+1)
            return i;
    }
}

v naetoNaPointers(int j = 12 ,int p = 70)
{
    int arrr[]={12,12,2,112,6,908,84,8,86,8,3,78,3,7,25};
    int n = sizeof(arrr)/sizeof(arrr[0]);
    const char* js = "asdasdas asd asd";
    char jjuu[] = " asdasd asdsa motivation inspiration action";
    int (*ge)(int,int) = add;
    nextt(j,p,ge);
    nullptr_t glods;
    ge = NULL;
    increasee(&p,sizeof(int));
    increasee(&js,sizeof(char));
    int (*well)(int,int)= &add ;
    well(12,23);
    int (*woaharay[])(int,int) = {add,sub,mul} ;
    woaharay[2](j,p);
    oh(geng);
    searchh(arrr,n,sizeof(int),&j,compare);
    int (*yes)(int,int)=add;
    return naetoNaPointers();
}

void pointersAgain()
{
    char s[2][4][34]={ { "koko" , "discipline" , "promise" } , { "trust" , "pledge" , "life" } };
    int arrr[]={123,3,233,3,3,3,321,314,876,96,567,4,456,456} ;
    int ars[2][2][2]= {  {{1,2},{3,4}} , {{7,8},{9,6} } };
    int (*palo)[14]=&arrr;
    std::cout<< *(ars) ;
    std::cout<< *(*(ars+1)+1 );
    std::cout<< *(*(*(ars +1)+1)+1);
    std::cout<< ars[1] << ars[1][1] << ars[1][1][1];

     int (*baho)[2][2] ;
     baho = ars;
     std::cout << baho << baho+1 << baho+2 ;
     std::cout << *baho << *(baho+1) << *(baho+2) ;
     std::cout << **baho << *(*(baho+1)+2) << *(*(baho+2)+3);

     const int ojt{46};
     const int ojLang{96};

     const int* const hey {&ojt};
     std::cout << hey << *hey;
}

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
//yes structures nadin sa wakas yohooooo!!


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

class Test
{
public:
    int main(int s)
    {
        cout << s << "\n";
        return 0;
    }
    int main(char *s)
    {
        cout << s << endl;
        return 0;
    }
    int main(int s ,int m)
    {
        cout << s << " " << m;
        return 0;
    }
};

#define FFF  paraSaIntMain();

template<typename ParaSaIntMainIto>
ParaSaIntMainIto asd {};

template <typename T>
T addByear(T &cyear,T &yyear,T curyear = 2024)
{
     cyear=curyear - cyear ;
     yyear=curyear - yyear ;
}

void intmain()
{
    int cb=0,yb=0;
    std::cout<< "Enter your year of birth:\n" ;
    std::cin>>yb;
    std::cout<< "Enter your crush year of birth:\n" ;
    std::cin>>cb;

    addByear(yb,cb);
    std::cout<< "\n Your  year of age: "<< yb ;
    std::cout<< "\n Your crush year of age: "<< cb ;

}

void fun()
{
    for (int i = 0; i < 9; i++) {
    }
}

// Driver Code
void mnain()
{
    // clock_t clock(void) returns the
    // number of clock ticks elapsed
    // after program was launched.
    clock_t start, end;

    // Recording the starting
    // clock tick
    start = clock();

    fun();

    // Recording the end clock tick
    end = clock();

    // Calculating total time taken
    // by the program
    double time_taken= double(end - start)/ double(CLOCKS_PER_SEC);

    cout << " Time taken by program is: "<< std::fixed<< time_taken<< std::setprecision(5);

    cout << " sec " << endl;


}

int main( long long int argc[51] , char* const argv[9459898456], Largest t )
{
    //std::string  ws = "\n" ;
    //Test obj;
    //obj.main(3);
    //obj.main("I love C++");
    //obj.main("w");
    //obj.main(9, 6);
    //mnain();
    FFF

    //OverWorldSecondo ows; templatesPractice(); paraSaIntMain(); preDefinedPreprocess();
    //ows.paraSaIntMain();
    /*short int arraysss[] = {1,2,4,5,3};
    short int arraysize = (sizeof(arraysss)/sizeof(int));
    std::cout  << "Array size:\t" << arraysize << " \n" ;
    printss();*/
    //argc[3] = 001010101010101010101010010101001010101010101010101001;
    //short int dss = argc[3] ;
    //binhiKo();
    //intmain();

}
/////////////////++++++++++++////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////y
