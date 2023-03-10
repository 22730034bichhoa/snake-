void ve(){
   void ve(Point Qua)
       {
          for i = 0;i < DoDai; i++)
             { 
               gotoxy(A[1].x, A[1].y);
               count << "x";
             }
          gotoxy( Qua.x , Qua.y);count<<"*";
       }
void DiChuyen(int Huong)
{
  void DiChuyen(int Huong,Point& Qua)
    {
      for (int i = DoDai-1; i>0;i--)
           A[i] = A[i-1];
      if (Huong==0) A[0].x = A[0].x + 1;
      if (Huong==1) A[0].y = A[0].y + 1;
      if (Huong==2) A[0].x = A[0].x - 1;
      if (Huong==3) A[0].y = A[0].y - 1;
    }
  
  
          
