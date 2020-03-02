
![喬治·斯蒂比茲](image/stibitz_portrait2.jpg?raw=true"喬治·斯蒂比茲")

# 喬治·斯蒂比茲（George Stibitz) 的繼電器計算機
> English version : https://history-computer.com/ModernComputer/Relays/Stibitz.html

### 譯者有話要說 Translator's Note

貝爾電話實驗室作為貝爾系統的基礎研究設施成立於1925年。
從此該機構變成了物理學，化學和其他領域之現代科學的前沿基礎研究以及令人興奮的研究課題的代名詞
在接下來的幾十年裡，這個激動人心的地方進行了大量研究，為好幾位發明家帶來諾貝爾獎。
許多計算機領域的發明在這裏誕生，在此僅提及邏輯上二極管的初次構想（1942），點接觸電晶體（point transistor）（1947），第一台全晶體管計算機（TRADIC，1955），第一台數據機（1960）， 第一個32位元單晶片處理器（1980），UNIX操作系統（1969），C程式語言（1973）和C++程式語言（1983）等。
![首個二進位繼電器加法器](image/ModelKStibitz.jpg?raw=true"首個二進位繼電器加法器")
1937年11月下旬，在貝爾實驗室的一位研究數學家喬治·斯蒂比茲（George Stibitz)（喬治·斯蒂比茲的傳記）從工作地點離開，回家時，從貝爾儲藏室拿走了兩個電話繼電器，幾個手電筒，以及電線和乾電池。在家裡，他坐在廚房桌子的後面，開始組裝一個由上述部件和煙錫製成的開關組成的簡單邏輯裝置。他很快有了一個設備，已被證明是首個二進位繼電器加法器（relays binary adder），點亮的燈泡代表二進位數字“1”，而未點亮的燈泡表示二進位數字“0”。他的妻子多蘿西婭（Dorothea）以“廚房桌子”將其命名為K模型。第二天，斯蒂比茲將K模型帶到實驗室向同事展示，然後他們推想以繼電器構建一個完整的計算器的可能性。他的同事認為，任何運用二進位運算的實用的繼電器計算機可能將會需要數百個繼電器，因此，與當時在實驗室使用的商用機械計算器相比，這使得它既笨重又昂貴。

但是，喬治·斯蒂比茲（George Stibitz）意識到，繼電器計算器不僅可以執行單個運算，還可以執行一系列計算，同時繼電器電路可以根據需要控制順序以及存儲臨時結果。具體來說，它可以執行運行複數乘法和複數除法所需的一系列操作————其他地方的研究人員在貝爾實驗室經常執行的兩項與設計長距離電路的濾波器和擴大機有關的數學運算。1930年代，一大堆人類“計算機”在實驗室中使用商用機械計算器計算出複數的商和乘積。計算本身非常簡單：複雜的乘法需要大約六個簡單的算術運算，而複雜的除法則需要大約十二個運算，每個運算都需要臨時存儲一些中間結果。

斯蒂比茲不知道在柏林的康拉德·楚澤（Konrad Zuse）在同一時間幾乎在做同樣的事情。 然而，斯蒂比茲知道克勞德·香農（Claude Shannon）還在麻省理工學院（MIT）研究生期間時也研究了符號邏輯語句與二進位繼電器電路的對應關係。 香農（Shannon）撰寫了有關該主題的研究生論文（於1938年出版），然後去了貝爾實驗室，在那裡他和斯蒂比茲（Stibitz）了解了彼此的工作。 但是香農並未積極參與斯蒂比茲的計算機設計。 顯然，使用繼電器實現二進位邏輯的想法在1930年代後期很普遍。 （日本也有類似的發現）。
![鍵盤](image/StibitzTerminalSchema.jpg?raw=true"鍵盤")

當Stibitz首次向公司高管演示他的K型計算機時，他們並不為之印象深刻。他後來記得，那裡既沒煙花，也沒有香檳。然而，不到一年之後，貝爾的高管們改變了對Stibitz發明的看法。做出此決定的重要因素是，貝爾尋求解決日益複雜的數學問題的方法的壓力越來越大。該公司同意資助Stibitz發明的大型實驗模型的建設。 Stibitz於1938年2月完成了設計，該機器的建造工作於1939年4月由貝爾的一位交換工程師撒母耳·威廉斯（Samuel Williams）開始進行。最終成品在10月準備就緒，並於1940年1月8日首次投入使用，一直使用到1949年。隨著貝爾實驗室在戰爭期間建造其他繼電器計算機，其名稱從最初的“複數計算機”更改為“模型1”。費用約為2萬美元。最初，複數計算機僅執行複雜的乘法和除法，但後來進行了簡單的修改，使其也可以進行加法和減法。它使用了大約400-450個二進位繼電器，6-8個面板，以及十多個位置稱為“橫桿”的多極繼電器，用於臨時存儲數字。機器使用十進制系統，小數點固定在每個數字的開頭。在內部，四個二進位繼電器對每個數字進行編碼，使用代碼n + 3的二進制代碼表示十進制數字n；這簡化了數字進位和減法的問題（今天，多三個的二進位編碼的十進制仍稱為“ Stibitz碼”）。 
機器在其暫存器中處理了十個位數的數字，但只顯示並印出了八位數的答案（範圍為？？0.99999999）(range ??0.99999999)。它使用“前綴”表示法：也就是說，鍵入操作數之前，運算符先鍵入算術運算。例如，要將兩個複數（2 + 3i）乘以（4 + 5i），操作員將鍵入（鍵盤 請參閱上方圖）：
   M +.2 + i .3 +.4 -i .5 =
   
字母M代表乘法（鍵盤上的字母D代表除法）。請注意小數點的位置在四個數字中的每個數字之前。機器實際上將計算（0.3 + 0.5i）x（0.4-0.2i），並輸出答案0.07000000 + i 0.22000000。操作員將不得不相應地縮放結果（乘以100）。一個簡單的加法運算大約需要100毫秒，而將2個複數相乘大約需要45秒。計算單元有4個暫存器，並且與作為特殊終端的輸入/輸出單元完全分開（請參見附近的照片）。計算機本身被保存在實驗室的一間偏僻房間中，很少有人見過。![終端機](image/StibitzTerminal.jpg?raw=true"終端機")
操作員使用三台經過修改的電傳打字機之一（鍵盤和打印設備）遠程訪問它，該電傳打字機通過一個束線匯流排連接到處理器，並放置在其他地方，但是不能同時工作。斯蒂比茲進一步發展了遠程，多線路同時訪問計算機的想法。 1940年9月11日，美國數學學會在新罕布什爾州漢諾威的達特茅斯學院會面，它位於紐約貝爾實驗室大樓以北數百英里處，那裡是複數計算機的所在地。 斯蒂比茲通過電話線（28線電傳打字電纜）將計算機連接到安裝在其中的電傳打字設備。複數計算機運行良好，毫無疑問，它給使用它的人留下了深刻的印象。許多美國最傑出的數學家以及後來領導重要的計算機項目的人（例如，約翰·馮·諾伊曼，約翰·莫赫利，諾伯特·維納和加勒特·伯克霍夫)(e.g., John von Neumann, John Mauchly, Norbert Wiener and Garrett Birkhoff)都參加了會議。
達特茅斯（Dartmouth）的演示預示了遠程計算的時代，但是這種類型的遠程訪問再過十年都沒有再現。
![複數計算機](image/CNCofStibitz.jpg?raw=true"複數計算機")
複數計算機無法編程。 繼電器電路的組合可永久控制其操作順序。 這些繼電器與用於處理數字的繼電器具有相同的類型，但是沒有單獨的，定義明確的部分來處理計算序列的“控制”。 （後來的貝爾實驗室計算機採用了這種方法。）貝爾實驗室（Bell Labs）在建造了複數計算機之後才出現了可編程性的概念，當時它的建造者看到了它的基本計算元素受到其與控制電路的聯結的過度限制，從而使它除了複雜的算術之外什麼都沒有。
（除了複數算法外，他們還嘗試使機器執行多項式算術，其中複數算術是一種特例。但是，這對機器來說太受限制了。）
複數計算機的成功鼓勵了Stibitz提出更具雄心的設計，其中包括可以通過穿孔的磁帶來修改計算器的操作。 起初，實驗室拒絕了他的提議，但是隨著美國在1941年12月加入第二次世界大戰，貝爾實驗室將其優先重點轉移到了軍事項目上，該項目所涉及的計算量超過其在和平時期的研究。 他們大部分的戰時成就都在類比計算機的設計中。 但是他們還建造了五台用於軍事目的的數位繼電器計算機，並在戰爭結束後又建造了一台供自己使用的數位繼電器計算機，從而使總共七台數位計算機計算出了複數計算機。這些用於軍事用途的計算器中的第一個是繼電器內插器，於1943年安裝在華盛頓特區，後來稱為Model II。它由440個繼電器構成，記憶體容量為7個數字。乘法速度為4秒（通過重複加法實現乘法）。它主要通過執行一系列算術運算來解決與指揮防空火力相關的問題，這些算術運算藉由紙帶內插函數值給機器。

像複數計算機一樣，它是一台專用計算機。但是，其算術序列不是由永久固定接線的繼電器計算器提供，而是由膠黏牢迴路的“公式膠帶”（五線紙帶）提供的。因此，不同的磁帶允許人們採用不同的插值方法。 Model II除了插值之外並不能做很多事情，但是由於插值過程可以解決科學和工程學中的許多問題，因此機器在戰爭結束後很久一直都被其他政府機構使用。The next two machines, designed by Stibitz are the Ballistic Computer and the Error Detector Mark 22 (later known as Models III and IV), were identical machines, the first installed in 1944 at Fort Bliss, Texas, and the second in early 1945 in Washington (each one cost 65000 USD). They contained some 1400 relays and had memory capacity of 10 numbers. Speed of multiplication was 1 second (multiplication by table look-up). These machines also used paper tapes for data and formula input, with the arithmetic sequence supplied by a loop of paper tape. The Models III and IV, like the Model II, also solved problems relating to the aiming and tracking of antiaircraft guns. They were, however, more sophisticated machines, having the ability not only to perform interpolation but also to evaluate the ballistic equations describing the path of the target airplane and of the antiaircraft shell. An additional paper tape directed which of those functions the machine was to evaluate. Thus, the Models III and N were the first of the Bell Labs digital calculators to have some degree of general programmability, although neither was a fully general-purpose calculator. Their memory and arithmetic units had modest capabilities: only six decimal digits of precision, a memory of ten numbers for each machine.

The largest computer in the series and the last, designed by Stibitz, was the Model V, of which Bell Labs built two copies for the military in 1946 and 1947. It was a huge (weight 10 tons) and very expensive (500000 USD) machine. Each contained over nine thousand relays and handled numbers expressed in scientific notation. The store could hold up to thirty numbers, and paper tape readers fed in both program steps and numerical data. Speed of multiplication 0.8 sec. The most interesting aspect of the Model V's design was that it had two separate arithmetic units, each capable of operating as an independent computer with its own memory registers and input-output devices. Small-scale problems could be run in pairs on the machine, saving time, while bigger problems could take over both processors. Associated with each processor (using the modern term) were fifteen memory registers, for a total of thirty for the whole machine. A master control unit directed instructions to one or both processors according to their availability. This control unit was separate from the control units in the processor that directed the sequence of arithmetic, memory, and input/output operations; it controlled the control, so to speak. (Stibitz called it a "superbranching" capability.) Thus in a very real sense the Model V had what is now called an "operating system"-a control unit that supervises and manages the flow of work through a computer.

Besides programming power, the later Bell computers stressed extraordinary reliability. Relays, used as a basic element for logical and memory operations, have a tendency to fail intermittently. Should a piece of dust lodge itself between two relay contacts, that circuit will fail, though the rest of the relay will be fine. After a few cycles, the dust particle may shake itself loose, after which everything will return to normal. Thus an entire computation may be way off without any machine failure showing up during a diagnostic session.

Bell's engineers designed computer circuits that checked themselves at every step of a computation. The circuits were designed not only to add, subtract, store numbers, and so on; they were also designed to check that they had done those things correctly, and to stop the machine otherwise. Bell's engineers were also guided by their experience in designing telephone circuits that had to operate long hours unattended in often hostile environments. Those circuits were designed to be repaired by semi-skilled technicians; telephone service would be terribly costly if an engineer had to be called in every time a phone line went down or a customer's phone went dead. The Bell Labs Models II through VI used a system whereby not four but seven binary relays coded each decimal digit. They were divided into two groups of two and five relays; the decimal code was as follows:

Decimal digit
Relays
0	01	00001
1	01	00010
2	01	00100
3	01	01000
4	01	10000
5	10	00001
6	10	00010
7	10	00100
8	10	01000
9	10	10000
Bell Labs called this system a "bi-quinary" notation, since the relays had a weight of either one or five. Actually, it is not a combination of those number bases; rather, it is a seven-bit, mixed decimal code. All the Bell Labs relay computers worked in decimal arithmetic. A special circuit checked to see that two and only two relays were energized for each decimal digit. Another circuit checked that for each group one and only one relay was on—that prevented two separate errors from canceling each other out, although certain unusual combinations of malfunctions could go undetected.
Relay computer : 繼電器計算機

institution : 機構

frontiers : 前沿

diodes : 二極管

point transistor : 	點接觸電晶體

transistor computer : 晶體管計算機

modem : 數據機

first single-chip 32-bit processor : 32位元單晶片處理器

mathematician : 數學家
stockroom 儲藏室
dry cell 乾電池
tobacco tin 煙錫
adder 加法器
speculated 推測
relays binary adder 二進位繼電器加法器
binary arithmetic 二進位算術/運算
Bulky 笨重的
 a sequence of 一系列
 interim 臨時
 directing 指揮
 filter 濾波器
amplifier  擴大機
a roomful of 滿屋子的
correspondence 對應
demonstrated 演示
executives 高管
experimental 實驗性的
 finance 資助
 panels 面板
 multiposition 多位的;多位置的;多極的
 crossbars 交叉棒，橫桿
 Internally 內部地
 registers 暫存器
 operand 操作數
 bus 匯流排
 teletype 電傳打字機
 multiple-wire 束線
 teletype 電傳打字機
 prominent 傑出的
 foreshadowed 預示
 era 時代
  unduly 過度地
arose 出現
marriage 合併
ambitious 雄心勃勃的
perforated 穿孔的
analog 類比
digital machine 數位計算機
Interpolator 內插器
antiaircraft fire 防空火力
cemented 粘牢
five-channel paper tape 五線紙帶
