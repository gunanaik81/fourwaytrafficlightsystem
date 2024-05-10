# fourwaytrafficlightsystem
sbit red1 at RB0_bit;
sbit yellow1 at RB1_bit;
sbit green1 at RB2_bit;

sbit red2 at RB3_bit;
sbit yellow2 at RB4_bit;
sbit green2 at RB5_bit;


void main() {
TRISB=0x00;


while(1)
{
red1=0;yellow1=0;green1=1;
red2=1;yellow2=0;green2=0;
delay_ms(1000);

red1=0;yellow1=1;green1=0;
red2=0;yellow2=1;green2=0;
delay_ms(1000);


red1=1;yellow1=0;green1=0;
red2=0;yellow2=0;green2=1;
delay_ms(1000);

red1=1;yellow1=0;green1=0;
red2=0;yellow2=1;green2=0;
delay_ms(1000);


red1=1;yellow1=0;green1=0;
red2=1;yellow2=0;green2=0;
delay_ms(1000);


red1=1;yellow1=0;green1=0;
red2=1;yellow2=0;green2=0;
delay_ms(1000);


red1=1;yellow1=0;green1=0;
red2=1;yellow2=0;green2=0;
delay_ms(1000);





}

}
