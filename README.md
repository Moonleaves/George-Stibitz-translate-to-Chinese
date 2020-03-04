
![喬治·斯蒂比茲](image/stibitz_portrait2.jpg?raw=true"喬治·斯蒂比茲")

# *喬治·斯蒂比茲（George Stibitz) 的繼電器計算機*
> English version : https://history-computer.com/ModernComputer/Relays/Stibitz.html

### 譯文如下

貝爾電話實驗室作為貝爾系統的基礎研究設施成立於1925年。從此該機構變成了物理學、化學和其他領域之現代科學的前沿基礎研究以及令人興奮的研究課題的代名詞，在接下來的幾十年裡，這個激動人心的地方進行了大量研究，為好幾位發明家帶來諾貝爾獎。
許多計算機領域的發明在這裏誕生，在此僅提及邏輯上二極管的初次構想（1942）、點接觸電晶體（point transistor）（1947）、第一台全晶體管計算機（TRADIC，1955）、第一台數據機（1960）、第一個32位元單晶片處理器（1980）、UNIX操作系統（1969）、C程式語言（1973）和C++程式語言（1983）等。

![首個二進位繼電器加法器](image/ModelKStibitz.jpg?raw=true"首個二進位繼電器加法器")

1937年11月下旬，在貝爾實驗室的一位研究數學家喬治·斯蒂比茲（George Stibitz)（喬治·斯蒂比茲的傳記）從工作地點離開。回家時，從貝爾儲藏室拿走了兩個電話繼電器，幾個手電筒，以及電線和乾電池。在家裡，他坐在廚房的桌子後面，開始組裝一個由上述部件和煙錫製成的開關組成的簡單邏輯裝置。他很快有了一個設備，已被證明是首個二進位繼電器加法器（relays binary adder），點亮的燈泡代表二進位數字“1”，而未點亮的燈泡表示二進位數字“0”。他的妻子多蘿西婭（Dorothea）以“廚房桌子”將其命名為K模型。第二天，斯蒂比茲將K模型帶到實驗室向同事展示，然後他們推想以繼電器構建一個完整的計算器的可能性。他的同事認為，任何運用二進位運算的實用的繼電器計算機可能將會需要數百個繼電器。因此，與當時在實驗室使用的商用機械計算器相比，這使得它既笨重又昂貴。

但是，喬治·斯蒂比茲（George Stibitz）意識到，繼電器計算器不僅可以執行單個運算，還可以執行一系列計算，同時繼電器電路可以根據需要控制順序以及存儲臨時結果。具體來說，它可以執行運行複數乘法和複數除法所需的一系列操作————其他地方的研究人員在貝爾實驗室經常執行的兩項與設計長距離電路的濾波器和擴大機有關的數學運算。1930年代，一大堆人類“計算機”在實驗室中使用商用機械計算器計算出複數的商和乘積。計算本身非常簡單：複雜的乘法需要大約六個簡單的算術運算；複雜的除法則需要大約十二個運算，每個運算都需要臨時存儲一些中間結果。

斯蒂比茲不知道在柏林的康拉德·楚澤（Konrad Zuse）在同一時間幾乎在做同樣的事情。 然而，斯蒂比茲知道克勞德·香農（Claude Shannon）還在麻省理工學院（MIT）研究生期間時也研究了符號邏輯語句與二進位繼電器電路的對應關係。 香農（Shannon）撰寫了有關該主題的研究生論文（於1938年出版），然後去了貝爾實驗室，在那裡他和斯蒂比茲（Stibitz）了解了彼此的工作。 但是香農並未積極參與斯蒂比茲的計算機設計。 顯然，使用繼電器實現二進位邏輯的想法在1930年代後期很普遍。 （日本也有類似的發現）。

![鍵盤](image/StibitzTerminalSchema.jpg?raw=true"鍵盤")

當Stibitz首次向公司高管演示他的K型計算機時，他們並不為之印象深刻。他後來記得，那裡既沒煙花，也沒有香檳。然而，不到一年之後，貝爾的高管們改變了對Stibitz發明的看法。該公司同意資助Stibitz發明的大型實驗模型的建設，做出此決定的重要因素是，貝爾尋求解決日益複雜的數學問題的方法的壓力越來越大。 Stibitz於1938年2月完成了設計，該機器的建造工作於1939年4月由貝爾的一位交換工程師撒母耳·威廉斯（Samuel Williams）開始進行。最終成品在10月準備就緒，並於1940年1月8日首次投入使用，一直使用到1949年。隨著貝爾實驗室在戰爭期間建造其他繼電器計算機，其名稱從最初的“複數計算機”更改為“模型1”，費用約為2萬美元。最初，複數計算機僅執行複雜的乘法和除法，但後來進行了簡單的修改，使其也可以進行加法和減法。它使用了大約400-450個二進位繼電器、6-8個面板以及十多個位置為稱為“橫桿”的多極繼電器，用於臨時存儲數字。機器使用十進制系統，小數點固定在每個數字的開頭。在內部，四個二進位繼電器對每個數字進行編碼，使用代碼n + 3的二進制代碼表示十進制數字n，這簡化了數字進位和減法的問題（今天，多三個的二進位編碼的十進制仍稱為“ Stibitz碼”）。 
機器在其暫存器中處理了十個位數的數字，但只顯示並印出了八個位數的答案（範圍為？？0.99999999）(range ??0.99999999)。它使用“前綴”表示法，也就是說：鍵入操作數之前，運算符先鍵入算術運算。例如，要將兩個複數（2 + 3i）乘以（4 + 5i），操作員將鍵入（鍵盤 請參閱上方圖）：

   M +.2 + i .3 +.4 -i .5 =
   
字母M代表乘法（鍵盤上的字母D代表除法），請注意小數點的位置在四個數字中的每個數字之前。機器實際上將計算（0.3 + 0.5i）x（0.4-0.2i），並輸出答案0.07000000 + i 0.22000000，操作員將不得不相應地縮放結果（乘以100）。一個簡單的加法運算大約需要100毫秒，而將2個複數相乘大約需要45秒。計算單元有4個暫存器，並且與作為特殊終端的輸入/輸出單元完全分開（請參見附近的照片）。計算機本身被保存在實驗室的一間偏僻房間中，很少有人見過。

![終端機](image/StibitzTerminal.jpg?raw=true"終端機")

操作員使用三台經過修改的電傳打字機之一（鍵盤和打印設備）遠程訪問它，該電傳打字機通過一個束線匯流排連接到處理器，並放置在其他地方，但是不能同時工作。斯蒂比茲進一步發展了遠程，多線路同時訪問計算機的想法。 1940年9月11日，美國數學學會在新罕布什爾州漢諾威的達特茅斯學院會面，它位於紐約貝爾實驗室大樓以北數百英里處，那裡是複數計算機的所在地。 斯蒂比茲通過電話線（28線電傳打字電纜）將計算機連接到安裝在其中的電傳打字設備。複數計算機運行良好，毫無疑問，它給使用它的人留下了深刻的印象。許多美國最傑出的數學家以及後來領導重要的計算機項目的人（例如，約翰·馮·諾伊曼、約翰·莫赫利、諾伯特·維納和加勒特·伯克霍夫)(e.g., John von Neumann, John Mauchly, Norbert Wiener and Garrett Birkhoff)都參加了會議。達特茅斯（Dartmouth）的演示預示了遠程計算的時代，但是這種類型的遠程訪問再過十年都沒有再現。

![複數計算機](image/CNCofStibitz.jpg?raw=true"複數計算機")

複數計算機無法編程，繼電器電路的組合可永久控制其操作順序。 這些繼電器與用於處理數字的繼電器具有相同的類型，但是沒有單獨的，定義明確的部分來處理計算序列的“控制”。 （後來的貝爾實驗室計算機採用了這種方法）

貝爾實驗室（Bell Labs）在建造了複數計算機之後才出現了可編程性的概念，當時它的建造者看到了它的基本計算元素受到其與控制電路的聯結的過度限制，從而使它除了複雜的算術之外什麼都沒有。（除了複數算法外，他們還嘗試使機器執行多項式算術，其中複數算術是一種特例。但是，這對機器來說太受限制了。）
複數計算機的成功鼓勵了Stibitz提出更具雄心的設計，其中包括可以通過穿孔的磁帶來修改計算器的操作。 起初，實驗室拒絕了他的提議，但是隨著美國在1941年12月加入第二次世界大戰，貝爾實驗室將其優先重點轉移到了軍事項目上，該項目所涉及的計算量超過其在和平時期的研究。 他們大部分的戰時成就都在類比計算機的設計中。 但是他們還建造了五台用於軍事目的的數位繼電器計算機，並在戰爭結束後又建造了一台供自己使用的數位繼電器計算機，從而使總共七台數位計算機計算出了複數計算機。這些用於軍事用途的計算器中的第一個是繼電器內插器，於1943年安裝在華盛頓特區，後來稱為Model II。它由440個繼電器構成，記憶體容量為7個數字，乘法速度為4秒（通過重複加法實現乘法）。它主要通過執行一系列算術運算來解決與指揮防空火力相關的問題，這些算術運算藉由紙帶內插函數值給機器。

像複數計算機一樣，它是一台專用計算機。但是，其算術序列不是由永久固定接線的繼電器計算器提供，而是由膠黏牢迴路的“公式膠帶”（五線紙帶）提供的。因此，不同的磁帶允許人們採用不同的插值方法。 Model II除了插值之外並不能做很多事情，但是由於插值過程可以解決科學和工程學中的許多問題，因此機器在戰爭結束後很久一直都被其他政府機構使用。接下來的兩台由Stibitz設計的機器是彈道計算機和Mark 22錯誤檢測器（後來稱為Model III和IV），它們是相同的機器。第一台安裝於1944年，位於德克薩斯州的布利斯堡；第二台安裝於1945年初的華盛頓（每個花費65000美元）。它們包含約1400個繼電器，並具有10個數字的記憶體容量，乘法速度為1秒（通過查表乘法）。這些機器還將紙帶用於數據和公式輸入，而其算術序列由紙帶循環提供。與模型II一樣，模型III和IV也解決了與高射砲的瞄準和跟踪相關的問題。但是，它們是更複雜的機器，不僅具有執行插值的能力，而且還能夠解出描述目標飛機和高射砲砲彈路徑的彈道方程。附加的紙帶指示機器要評估哪些功能。因此，Model III和Model N是Bell Labs中第一個具有一定程度的通用可編程性的數位計算器，儘管它們都不是完全通用的計算器。他們的內存和算術單元能力極低：只有六位十進制數字的精度，每台機器可存儲十個數字。該系列中最大的計算機也是最後一台計算機，Model V，由Stibitz設計。貝爾實驗室在1946年和1947年為軍方製造了兩台Model V。

這是一台巨大的計算機（重10噸），非常昂貴（500000美元）。每台包含九千多個繼電器，並以科學計數法表示處理的數字。儲存空間最多可以容納三十個數字，並且紙帶讀取器可以同時讀取程序步驟和數字的數據，乘法速度0.8秒。Model V的設計最有趣的方面是它具有兩個獨立的算術單元，每個算術單元都可以作為具有自己的內存暫存器和輸入輸出設備的獨立計算機操作。小型問題可以在計算機上成對運行，從而節省時間；而較大的問題可以兼併兩個處理器。與每個處理器相聯（使用現代術語）的是15個記憶體暫存器，整個機器總共有30個。主控制單元根據其可用性將指令指揮到一個或兩個處理器。該控制單元與處理器中控制運算，暫存器和輸入/輸出操作順序的控制單元是分開的。它可以控制控件，可以這麼說。（Stibitz稱其為“超級分支”能力。） 因此，從真正的意義上講，Model V具有現在所謂的“操作系統”：一個監督和管理通過計算機的工作流程的控制單元。

除了編程能力，後來的貝爾計算機還注重非凡的可靠性。用作邏輯和記憶體操作的基本元素的繼電器有間歇性故障的趨勢。 如果在兩個繼電器觸點之間有灰塵積聚，則該電路將發生故障，儘管繼電器的其餘部分都好好的。幾次循環後，灰塵顆粒可能會自行晃動，鬆脫然後一切恢復正常。因此，整個計算可能會偏離，而在診斷期間不會出現任何機器故障。


貝爾的工程師設計了，可以在計算的每個步驟進行自我檢查的計算機電路。 該電路不僅要增加、減去、儲存數字等等。 它們還被設計為可自我檢測是否正確完成了這些操作，否則停止機器。 貝爾的工程師還以其設計電話電路的經驗為借鑑，這些電話電路必須經常在無人值守的惡劣環境下長時間運轉。 這些電路設計為可被半熟練的技術人員進行維修，如果每次電話線掉線或客戶的電話壞了時都要打電話給工程師，電話服務的成本將會非常高。Bell Labs II至VI模型使用的系統中，為每個十進制數字編碼的不是四個而是七個二進位繼電器。 它們分為兩組：兩個和五個繼電器。 十進制代碼如下：

| 十進制數字 |繼電器 |繼電器  |
|-------|---------|----------|
|0	|01	|00001|
|1	|01	|00010|
|2	|01	|00100|
|3	|01	|01000|
|4	|01	|10000|
|5	|10	|00001|
|6	|10	|00010|
|7	|10	|00100|
|8	|10	|01000|
|9	|10	|10000|

貝爾實驗室稱此系統為*二五進制記法*，因為繼電器的權重為一或五。 實際上，它不是這些數字基礎的組合，而是一個七比特混合的十進制代碼。 所有的貝爾實驗室的繼電器計算機都以十進制算法工作。 一個特殊的電路檢查確保每個十進制數字只能有兩個繼電器通電；另一個電路則檢查每個組中只能有一個繼電器是通電狀態，這可以防止兩個單獨的錯誤相互抵消，儘管某些異常組合可能無法檢測到。

### 生詞
Relay computer 繼電器計算機<br>
institution 機構<br>
frontiers 前沿<br>
diodes 二極管<br>
point transistor 點接觸電晶體<br>
transistor computer 晶體管計算機<br>
modem 數據機<br>
first single-chip 32-bit processor 32位元單晶片處理器<br>
mathematician 數學家<br>
stockroom 儲藏室<br>
dry cell 乾電池<br>
tobacco tin 煙錫
adder 加法器<br>
speculated 推測<br>
relays binary adder 二進位繼電器加法器<br>
binary arithmetic 二進位算術/運算<br>
Bulky 笨重的<br>
 a sequence of 一系列<br>
 interim 臨時<br>
 directing 指揮<br>
 filter 濾波器<br>
amplifier  擴大機<br>
a roomful of 滿屋子的<br>
correspondence 對應<br>
demonstrated 演示<br>
executives 高管<br>
experimental 實驗性的<br>
 finance 資助<br>
 panels 面板<br>
 multiposition 多位的;多位置的;多極的<br>
 crossbars 交叉棒，橫桿<br>
 Internally 內部地<br>
 registers 暫存器<br>
 operand 操作數<br>
 bus 匯流排<br>
 teletype 電傳打字機<br>
 multiple-wire 束線<br>
 teletype 電傳打字機<br>
 prominent 傑出的<br>
 foreshadowed 預示<br>
 era 時代<br>
  unduly 過度地<br>
arose 出現<br>
marriage 合併<br>
ambitious 雄心勃勃的<br>
perforated 穿孔的<br>
analog 類比<br>
digital machine 數位計算機<br>
Interpolator 內插器<br>
antiaircraft fire 防空火力<br>
cemented 粘牢<br>
five-channel paper tape 五線紙帶<br>
Ballistic 彈道<br>
memory capacity 記憶體容量<br>
aiming 瞄準<br>
antiaircraft guns 高射砲<br>
sophisticated 複雜的<br>
antiaircraft shell 高射砲彈<br>
modest 謙卑<br>
fed in 餵<br>
aspect 方面<br>
take over 兼併<br>
availability 可用性<br>
capability 能力<br>
supervises 監督<br>
stressed 注重<br>
lodge 小屋<br>
loose 疏鬆<br>
diagnostic session 診斷會議<br>
 unattended 無人值守<br>
 hostile 敵對的<br>
 semi-skilled 半熟練的<br>
 bi-quinary notation 二五進制記法<br>
 energized 通電<br>
canceling...out 抵銷<br>
separate 個別的<br>
