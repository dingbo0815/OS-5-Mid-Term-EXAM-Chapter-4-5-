# OS-5-Mid-Term-EXAM-Chapter-4-5-
ch4.
第4章的目的是利用while迴圈瘋狂增加任務讓燈迅速的瘋狂輪流閃，在main cpp和另外的blinkagent都有做修改，而修改部分為oid mainTask(void *params)定義要測試的任務數量 (例如從 10 開始往上加，直到系統崩潰)
CH5
一開始把板子接到擴充板時裝反了，所以一直以為是接腳沒有打對，在程式增加LED4並把LED0接腳改為0，因為有四個燈但只有兩個token，所以就會輪流亮燈，有優先順序，並在terminal 觀察了其中的task值等數據，擴充板讓原本樹梅派板子只有兩顆登能閃變成很多pin腳都有各自的燈能用
