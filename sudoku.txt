function resuelvesudoku(){
var sudoku1  = [[0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0]];  

var sudoku3  = [[0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0],
                [0,0,0,0,0,0,0,0,0]];  


var num00 = Number(document.getElementById("num00").value);
var num01 = Number(document.getElementById("num01").value);
var num02 = Number(document.getElementById("num02").value);
var num03 = Number(document.getElementById("num03").value);
var num04 = Number(document.getElementById("num04").value);
var num05 = Number(document.getElementById("num05").value);
var num06 = Number(document.getElementById("num06").value);
var num07 = Number(document.getElementById("num07").value);
var num08 = Number(document.getElementById("num08").value);
var num10 = Number(document.getElementById("num10").value);
var num11 = Number(document.getElementById("num11").value);
var num12 = Number(document.getElementById("num12").value);
var num13 = Number(document.getElementById("num13").value);
var num14 = Number(document.getElementById("num14").value);
var num15 = Number(document.getElementById("num15").value);
var num16 = Number(document.getElementById("num16").value);
var num17 = Number(document.getElementById("num17").value);
var num18 = Number(document.getElementById("num18").value);
var num20 = Number(document.getElementById("num20").value);
var num21 = Number(document.getElementById("num21").value);
var num22 = Number(document.getElementById("num22").value);
var num23 = Number(document.getElementById("num23").value);
var num24 = Number(document.getElementById("num24").value);
var num25 = Number(document.getElementById("num25").value);
var num26 = Number(document.getElementById("num26").value);
var num27 = Number(document.getElementById("num27").value);
var num28 = Number(document.getElementById("num28").value);
var num30 = Number(document.getElementById("num30").value);
var num31 = Number(document.getElementById("num31").value);
var num32 = Number(document.getElementById("num32").value);
var num33 = Number(document.getElementById("num33").value);
var num34 = Number(document.getElementById("num34").value);
var num35 = Number(document.getElementById("num35").value);
var num36 = Number(document.getElementById("num36").value);
var num37 = Number(document.getElementById("num37").value);
var num38 = Number(document.getElementById("num38").value);
var num40 = Number(document.getElementById("num40").value);
var num41 = Number(document.getElementById("num41").value);
var num42 = Number(document.getElementById("num42").value);
var num43 = Number(document.getElementById("num43").value);
var num44 = Number(document.getElementById("num44").value);
var num45 = Number(document.getElementById("num45").value);
var num46 = Number(document.getElementById("num46").value);
var num47 = Number(document.getElementById("num47").value);
var num48 = Number(document.getElementById("num48").value);
var num50 = Number(document.getElementById("num50").value);
var num51 = Number(document.getElementById("num51").value);
var num52 = Number(document.getElementById("num52").value);
var num53 = Number(document.getElementById("num53").value);
var num54 = Number(document.getElementById("num54").value);
var num55 = Number(document.getElementById("num55").value);
var num56 = Number(document.getElementById("num56").value);
var num57 = Number(document.getElementById("num57").value);
var num58 = Number(document.getElementById("num58").value);
var num60 = Number(document.getElementById("num60").value);
var num61 = Number(document.getElementById("num61").value);
var num62 = Number(document.getElementById("num62").value);
var num63 = Number(document.getElementById("num63").value);
var num64 = Number(document.getElementById("num64").value);
var num65 = Number(document.getElementById("num65").value);
var num66 = Number(document.getElementById("num66").value);
var num67 = Number(document.getElementById("num67").value);
var num68 = Number(document.getElementById("num68").value);
var num70 = Number(document.getElementById("num70").value);
var num71 = Number(document.getElementById("num71").value);
var num72 = Number(document.getElementById("num72").value);
var num73 = Number(document.getElementById("num73").value);
var num74 = Number(document.getElementById("num74").value);
var num75 = Number(document.getElementById("num75").value);
var num76 = Number(document.getElementById("num76").value);
var num77 = Number(document.getElementById("num77").value);
var num78 = Number(document.getElementById("num78").value);
var num80 = Number(document.getElementById("num80").value);
var num81 = Number(document.getElementById("num81").value);
var num82 = Number(document.getElementById("num82").value);
var num83 = Number(document.getElementById("num83").value);
var num84 = Number(document.getElementById("num84").value);
var num85 = Number(document.getElementById("num85").value);
var num86 = Number(document.getElementById("num86").value);
var num87 = Number(document.getElementById("num87").value);
var num88 = Number(document.getElementById("num88").value);
var nums00 = Number(num00);
var nums01 = Number(num01);
var salida = 0;

sudoku1[0][0]= num00;
sudoku1[0][1]= num01;
sudoku1[0][2]= num02;
sudoku1[0][3]= num03;
sudoku1[0][4]= num04;
sudoku1[0][5]= num05;
sudoku1[0][6]= num06;
sudoku1[0][7]= num07;
sudoku1[0][8]= num08;

sudoku1[1][0]= num10;
sudoku1[1][1]= num11;
sudoku1[1][2]= num12;
sudoku1[1][3]= num13;
sudoku1[1][4]= num14;
sudoku1[1][5]= num15;
sudoku1[1][6]= num16;
sudoku1[1][7]= num17;
sudoku1[1][8]= num18;

sudoku1[2][0]= num20;
sudoku1[2][1]= num21;
sudoku1[2][2]= num22;
sudoku1[2][3]= num23;
sudoku1[2][4]= num24;
sudoku1[2][5]= num25;
sudoku1[2][6]= num26;
sudoku1[2][7]= num27;
sudoku1[2][8]= num28;

sudoku1[3][0]= num30;
sudoku1[3][1]= num31;
sudoku1[3][2]= num32;
sudoku1[3][3]= num33;
sudoku1[3][4]= num34;
sudoku1[3][5]= num35;
sudoku1[3][6]= num36;
sudoku1[3][7]= num37;
sudoku1[3][8]= num38;

sudoku1[4][0]= num40;
sudoku1[4][1]= num41;
sudoku1[4][2]= num42;
sudoku1[4][3]= num43;
sudoku1[4][4]= num44;
sudoku1[4][5]= num45;
sudoku1[4][6]= num46;
sudoku1[4][7]= num47;
sudoku1[4][8]= num48;

sudoku1[5][0]= num50;
sudoku1[5][1]= num51;
sudoku1[5][2]= num52;
sudoku1[5][3]= num53;
sudoku1[5][4]= num54;
sudoku1[5][5]= num55;
sudoku1[5][6]= num56;
sudoku1[5][7]= num57;
sudoku1[5][8]= num58;

sudoku1[6][0]= num60;
sudoku1[6][1]= num61;
sudoku1[6][2]= num62;
sudoku1[6][3]= num63;
sudoku1[6][4]= num64;
sudoku1[6][5]= num65;
sudoku1[6][6]= num66;
sudoku1[6][7]= num67;
sudoku1[6][8]= num68;

sudoku1[7][0]= num70;
sudoku1[7][1]= num71;
sudoku1[7][2]= num72;
sudoku1[7][3]= num73;
sudoku1[7][4]= num74;
sudoku1[7][5]= num75;
sudoku1[7][6]= num76;
sudoku1[7][7]= num77;
sudoku1[7][8]= num78;

sudoku1[8][0]= num80;
sudoku1[8][1]= num81;
sudoku1[8][2]= num82;
sudoku1[8][3]= num83;
sudoku1[8][4]= num84;
sudoku1[8][5]= num85;
sudoku1[8][6]= num86;
sudoku1[8][7]= num87;
sudoku1[8][8]= num88;
/*------- falta  --------------*/
var encontro =0;
for (let  k = 1; k < 10; k++)
 {
  
 for (let  i = 0; i < sudoku1.length; i++)
     {

         encontro = 0;
         for (let  j = 0; j < sudoku1.length; j++)
             {
                 if (sudoku1[i][j]==k)
                     {
                         encontro = 1;
                         j=10;
                     }
             }
             if (encontro == 0)
             {
                 sudoku3[i][k-1]=k;
             }
      }
 }


console.log ("ESTOS SONLOS NUMEROS QUE FALTAN DEL SUDOKO");
console.log();
for (let  i = 0 ; i < sudoku3.length ; i++)
{
 console.log(sudoku3[i]);
}

/*-------------resuelve--------*/
let inif = 0;
let inic = 0;
let llevo = 0;
let aux = 0;
let x=0;
let nosepuede = 0;
let h=0,i=0,j=0,k=0,l,m,n;
for ( x = 0; x < 10 ; x++)
{
    
    for (i = 0; i < 9; i++)
    {

    for ( j = 0; j < 9; j++)
    {

        if(sudoku3[i][j] !=0)
        {
            llevo = 0;
            
            for ( h = 0; h < 9; h++)
            {

                if (sudoku1[i][h] == 0)
                {
                    nosepuede=0;
                    for ( k = 0; k < 9 ; k++)
                    {

                        if (sudoku1[k][h]==sudoku3[i][j])
                            {
                                nosepuede=1;
                                k=9;
                            }                
                    }
                    if (nosepuede==0)
                    {        
                        switch (i)
                        {
                            case 0:
                                inif = 0;        /* define el inicio de la fila a buscar en el sector */
                                break;
                            case 1:
                                inif = 0;        /* define el inicio de la fila a buscar en el sector */
                               break;

                            case 2:
                                inif = 0;        /* define el inicio de la fila a buscar en el sector */
                               break;

                            case 3:
                                inif = 3;        /* define el inicio de la fila a buscar en el sector */
                              break;
                
                            case 4:
                                inif = 3;        /* define el inicio de la fila a buscar en el sector */
                              break;

                            case 5:
                                inif = 3;        /* define el inicio de la fila a buscar en el sector */
                                break;

                            case 6:
                                inif = 6;        /* define el inicio de la fila a buscar en el sector */
                                break;

                            case 7:
                               inif = 6;        /* define el inicio de la fila a buscar en el sector */
                                break;

                            case 8:
                                break;


                        }
                        switch (h)
                        {
                            case 0:
                                inic = 0;        /* define el inicio de la fila a buscar en el sector */
                               break;
                            case 1:
                                inic = 0;        /* define el inicio de la fila a buscar en el sector */
                                break;

                            case 2:
                                inic = 0;        /* define el inicio de la fila a buscar en el sector */
                                break;

                            case 3:
                                inic = 3;        /* define el inicio de la fila a buscar en el sector */
                                break;
                
                            case 4:
                                inic = 3;        /* define el inicio de la fila a buscar en el sector */
                                break;

                            case 5:
                                inic = 3;        /* define el inicio de la fila a buscar en el sector */
                                break;

                            case 6:
                                inic = 6;        /* define el inicio de la fila a buscar en el sector */
                                break;

                            case 7:
                                inic = 6;        /* define el inicio de la fila a buscar en el sector */
                                break;

                            case 8:
                                inic = 6;        /* define el inicio de la fila a buscar en el sector */
                                break;


                        }
                        
                        for ( m = inif; m < (inif+3); m++)
                        {
                            for ( l = inic; l < (inic+3); l++)
                            {
                                if (sudoku1[m][l]==sudoku3[i][j])
                                {
                                    nosepuede=1;
                                    l=inic+4;
                                    m=inif+4;
                                }                
                            }

                        }
                            
                        if (nosepuede == 0)
                        {
                            llevo = llevo +1;
                            aux = h;
                        }
                    }

                }
            }
        }
        if (llevo==1)
        {    
           sudoku1[i][aux]=sudoku3[i][j];
           sudoku3[i][j]=0;
           llevo=0;
                               
        }
    }

}

}

console.log ("ESTE ES EL RESULTADO  DEL SUDOKU");
console.log();
for (let  i = 0 ; i < sudoku3.length ; i++)
{
 console.log(sudoku1[i]);
}

 document.getElementById("respuesta").innerHTML =   sudoku1[0] + "<br>" +
                                                    sudoku1[1] + "<br>" +
                                                    sudoku1[2] + "<br>" +
                                                    sudoku1[3] + "<br>" +
                                                    sudoku1[4] + "<br>" +
                                                    sudoku1[5] + "<br>" +
                                                    sudoku1[6] + "<br>" +
                                                    sudoku1[7] + "<br>" +
                                                    sudoku1[8] ;


   
}
    
