<p align="center">
  <a href="https://genoffice.ai/">
    <picture>
      <source srcset="docs/assets/readme/hero-dark.webp" media="(prefers-color-scheme: dark)">
      <img src="docs/assets/readme/hero.webp" alt="GenOffice — bộ ứng dụng văn phòng AI mã nguồn mở: Docs, Sheets, Slides, PDF, Markdown và HTML với panel AI tích hợp sẵn" width="100%">
    </picture>
  </a>
</p>

<h1 align="center">GenOffice</h1>
<p align="center"><b>Bộ ứng dụng văn phòng AI mã nguồn mở đầy đủ tính năng đầu tiên trên thế giới.</b><br>
File Word, Excel, PowerPoint và PDF — bạn và AI cùng chỉnh sửa, lưu lại đúng định dạng gốc.</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/github/license/quyen2867/genoffice" alt="Giấy phép: Apache-2.0"></a>
  <a href="https://github.com/quyen2867/genoffice/releases/latest"><img src="https://img.shields.io/github/v/release/quyen2867/genoffice" alt="Bản phát hành mới nhất"></a>
  <a href="https://github.com/quyen2867/genoffice/releases"><img src="https://img.shields.io/github/downloads/quyen2867/genoffice/total" alt="Lượt tải"></a>
  <a href="https://github.com/quyen2867/genoffice/stargazers"><img src="https://img.shields.io/github/stars/quyen2867/genoffice?style=flat" alt="Sao GitHub"></a>
  <a href="https://x.com/merrickbuilds"><img src="https://img.shields.io/badge/follow-%40merrickbuilds-000000?logo=x&logoColor=white" alt="Theo dõi @merrickbuilds trên X"></a>
</p>

<p align="center"><b>Tiếng Việt</b> · <a href="https://github.com/genspark-ai/genoffice/blob/main/README.md">English</a> · <a href="docs/i18n/README.es.md">Español</a> · <a href="docs/i18n/README.pt-BR.md">Português (Brasil)</a> · <a href="docs/i18n/README.de.md">Deutsch</a> · <a href="docs/i18n/README.fr.md">Français</a> · <a href="docs/i18n/README.zh-CN.md">简体中文</a> · <a href="docs/i18n/README.zh-TW.md">繁體中文</a> · <a href="docs/i18n/README.ko.md">한국어</a> · <a href="docs/i18n/README.ja.md">日本語</a> · <a href="docs/i18n/README.ar.md">العربية</a> · <a href="docs/i18n/README.ru.md">Русский</a> · <a href="docs/i18n/README.it.md">Italiano</a> · <a href="docs/i18n/README.nl.md">Nederlands</a> · <a href="docs/i18n/README.pl.md">Polski</a> · <a href="docs/i18n/README.cs.md">Čeština</a> · <a href="docs/i18n/README.id.md">Bahasa Indonesia</a> · <a href="docs/i18n/README.ms.md">Bahasa Melayu</a> · <a href="docs/i18n/README.th.md">ไทย</a> · <a href="docs/i18n/README.hi.md">हिन्दी</a> · <a href="docs/i18n/README.he.md">עברית</a></p><!-- lang-switcher · public-hygiene: allow -->

<p align="center">
  <a href="#tải-xuống"><b>Tải về</b></a> ·
  <a href="#command-line-and-agent-skill"><b>CLI</b></a> ·
  <a href="#mcp-server"><b>MCP</b></a> ·
  <a href="https://genoffice.ai/"><b>Trang web</b></a> ·
  <a href="https://genoffice.ai/join"><b>Cộng đồng</b></a> ·
  <a href="https://x.com/merrickbuilds"><b>X</b></a> ·
  <a href="PRIVACY.md"><b>Quyền riêng tư</b></a>
</p>

GenOffice là giải pháp thay thế miễn phí, mã nguồn mở cho Microsoft Office trên
macOS, Windows và Linux. Nó mở và lưu file `.docx`, `.xlsx` và `.pptx` gốc,
chỉnh sửa PDF, Markdown và HTML, đồng thời đặt một AI agent ngay cạnh mỗi tài
liệu — không phải khung chat gắn thêm cho có, mà là một trình soạn thảo đọc
file, thực hiện thay đổi và cho bạn thấy chính xác những gì nó đã chạm vào.

- **Định dạng gốc, giữ nguyên từng byte.** Chỉ phần bạn chỉnh sửa mới được ghi
  lại. Mọi thứ còn lại trong file được giữ nguyên từng byte, nên tài liệu vẫn
  mở ngon lành trong Word, Excel và PowerPoint.
- **AI mà bạn kiểm soát được.** Mọi chỉnh sửa hiển thị dưới dạng theo dõi thay
  đổi (tracked changes) và diff, hoàn tác chỉ bằng một cú nhấp. Bảng tính dùng
  công thức thật, không phải số dán cứng. Slide và trang web được dựng trực
  tiếp lên canvas và vẫn chỉnh sửa đầy đủ được.
- **Cục bộ ngay từ thiết kế.** Mở, sửa, lưu và chuyển đổi file ngay trên máy
  của bạn. PDF → Word / Excel / PowerPoint, Markdown → Word và HTML → Word đều
  chạy trên thiết bị. Chỉ các lệnh gọi AI mới rời khỏi máy, tới nhà cung cấp do
  bạn chọn.
- **Tìm file theo nội dung.** Màn hình chính tìm kiếm theo tên, thư mục và toàn
  văn nội dung file `.docx`, `.xlsx`, `.pptx`, PDF, Markdown và HTML của bạn từ
  chỉ mục SQLite cục bộ, hỗ trợ cả CJK. Tuỳ chọn: các kết quả hàng đầu được xếp
  hạng lại bởi **[TypeSafe Jev](https://typesafe.ai/)**, mô hình đánh giá
  System One, để file trả lời đúng câu hỏi của bạn lên đầu tiên.
- **Dùng key của bạn, hoặc không cần key.** Đăng nhập bằng Genspark để khỏi cần
  key, hoặc dùng key của riêng bạn cho Claude, OpenAI, Gemini, DeepSeek, Kimi,
  GLM, Qwen, Doubao, MiniMax, Grok, Mistral, OpenRouter, Requesty, Opper, hay
  bất kỳ endpoint tương thích OpenAI nào, kể cả server chạy local.
- **Viết script được, sẵn sàng cho agent.** App đi kèm dòng lệnh `genoffice` và
  skill cho Claude Code, Codex, Cursor, Gemini CLI, GitHub Copilot, OpenCode và
  Windsurf, để coding agent có thể tạo, chuyển đổi, đọc và sửa file Office thật
  ngay trên máy bạn mà không cần mở cửa sổ nào.

**Tải ngay:** [macOS](https://github.com/quyen2867/genoffice/releases/latest) (Apple Silicon và Intel) ·
[Windows](https://github.com/quyen2867/genoffice/releases/latest) (x64 và Arm) ·
[Linux](https://github.com/quyen2867/genoffice/releases/latest) (deb, rpm, AppImage) —
chi tiết và yêu cầu hệ thống xem tại [Tải về](#tải-xuống).

## Demo

Sáu ứng dụng, một panel AI, tìm kiếm file được xếp hạng lại bởi TypeSafe Jev, và
dòng lệnh cho coding agent của bạn. Mọi ảnh chụp màn hình đều là app thật trên
macOS, với AI được điều khiển từ prompt mà bạn có thể đọc ngay trong panel.

### 1 · Docs — mở và sửa `.docx` với AI mà bạn kiểm soát được

<table>
<tr>
<td width="50%"><img src="docs/assets/readme/docs-report.webp" alt="GenOffice Docs hiển thị trang báo cáo thường niên hai cột với ảnh bìa tràn chiều rộng, bảng KPI tô nền, header và footer, ở mức zoom 80% với panel AI thu gọn"></td>
<td width="50%"><img src="docs/assets/readme/docs-ai.webp" alt="GenOffice Docs: trang tổng quan công ty với ảnh banner; AI đã gọn lại phần Tổng quan và chèn thêm mục gạch đầu dòng mới, panel có nút hoàn tác một cú nhấp"></td>
</tr>
<tr>
<td><b>Mở file đúng như Word trình bày</b> — mục hai cột, ảnh tràn lề, bảng tô nền, header và footer, phân trang theo chuẩn dòng của Word. Style, bình luận, theo dõi thay đổi, công thức và nét vẽ tay đều giữ nguyên vẹn khi mở đi mở lại.</td>
<td><b>Ra lệnh sửa</b> — AI đọc các khối cần thiết, viết lại phần Tổng quan và chèn mục gạch đầu dòng mới. Mỗi lượt AI là một snapshot có thể hoàn tác; khi bật <b>Theo dõi thay đổi</b>, các chỉnh sửa hiện lên như revision kiểu Word.</td>
</tr>
</table>

### 2 · Sheets — `.xlsx` với công thức thật và biểu đồ, không phải số dán cứng

<table>
<tr>
<td width="50%"><img src="docs/assets/readme/sheets-ai.webp" alt="GenOffice Sheets: AI đã thêm sheet Tổng hợp doanh thu theo khu vực và danh mục bằng công thức SUMIF, kèm biểu đồ cột, và báo 43 thay đổi đã áp dụng với nút Hoàn tác"></td>
<td width="50%"><img src="docs/assets/readme/sheets-qa.webp" alt="GenOffice Sheets: khi được hỏi khu vực nào dẫn đầu doanh thu Q2, AI trả lời châu Âu kèm chi tiết theo danh mục và trích dẫn các ô đã dùng dưới dạng liên kết, bên cạnh sheet Đơn hàng"></td>
</tr>
<tr>
<td><b>Dựng bảng</b> — chỉ từ một câu lệnh, agent thêm sheet Tổng hợp với <code>SUMIF</code> thật theo khu vực và danh mục, chèn biểu đồ cột, và áp dụng 43 thay đổi thành một batch hoàn tác được.</td>
<td><b>Hỏi đáp</b> — câu hỏi về workbook được trả lời kèm lập luận và trích dẫn chính xác các ô đã dùng dưới dạng liên kết. Bên dưới: engine <code>.xlsx</code> viết bằng Rust của nhà làm, pivot table, slicer, định dạng có điều kiện và truy vết công thức.</td>
</tr>
</table>

### 3 · Slides — từ một prompt thành bộ slide `.pptx`

<img src="docs/assets/readme/slides-generate.webp" alt="Ảnh tua nhanh GenOffice Slides đang dựng bộ slide gọi vốn Aurora Home: AI lên dàn ý câu chuyện trong panel, các slide hiện dần lên canvas, và bộ slide hoàn chỉnh kết thúc bằng lời kêu gọi đầu tư" width="100%">

<table>
<tr>
<td width="50%"><img src="docs/assets/readme/slides-cover.webp" alt="GenOffice Slides: slide bìa của bộ slide gọi vốn Aurora Home do AI dựng trên canvas, với prompt một dòng gốc và tóm tắt của AI về những gì đã làm trong panel"></td>
<td width="50%"><img src="docs/assets/readme/slides-ai.webp" alt="GenOffice Slides: slide kết thúc đã thiết kế của cùng bộ 11 slide, với dải thumbnail bên trái và panel AI tóm tắt mạch câu chuyện"></td>
</tr>
<tr>
<td><b>Một dòng vào</b> — "Tạo bộ slide gọi vốn 10 slide cho Aurora Home…". GenOffice lên dàn ý, nghiên cứu số liệu và dựng từng slide lên canvas thành file <code>.pptx</code> thật.</td>
<td><b>Bộ slide hoàn chỉnh ra</b> — mười một slide được thiết kế với typography, hình ảnh nhất quán và lời kêu gọi hành động ở cuối; tiếp tục chỉnh sửa với master, layout, smart guide và crop không phá huỷ, hoặc nhờ panel đổi phong cách, viết lại và sắp xếp lại.</td>
</tr>
</table>

### 4 · PDF — sửa text PDF ngay tại chỗ, chuyển PDF sang Word trên thiết bị

<table>
<tr>
<td width="50%"><img src="docs/assets/readme/pdf-edit.webp" alt="GenOffice PDF: chế độ Sửa text khoanh vùng mọi khối text trên trang để sửa tại chỗ, trong khi panel AI trả lời câu hỏi về báo cáo kèm trích dẫn số trang"></td>
<td width="50%"><img src="docs/assets/readme/pdf-convert.webp" alt="GenOffice Docs hiển thị tài liệu Word được chuyển đổi cục bộ từ PDF báo cáo quý Helios, mở trong tab thứ hai cạnh PDF gốc"></td>
</tr>
<tr>
<td><b>Sửa ngay trong trang</b> — chế độ Sửa text khoanh vùng mọi khối text để gõ lại tại chỗ; luồng nội dung được ghi lại qua PDFium với font gốc, không phải chú thích che phủ. Hỏi AI về báo cáo dài và nhận câu trả lời kèm trích dẫn số trang.</td>
<td><b>Chuyển đổi trên thiết bị</b> — <b>PDF Converter → PDF sang Word</b> cho ra file <code>.docx</code> chỉnh sửa được, mở trong Docs ngay cạnh file gốc, giữ nguyên heading, hàng số liệu và đoạn văn. Chuyển sang Excel và PowerPoint cũng tương tự; trang scan đi qua OCR của hệ thống.</td>
</tr>
</table>

### 5 · HTML — trình dựng trang web và UI bằng AI, brief thiết kế trước

Nói trang web dùng để làm gì và cho ai. AI đề xuất **brief thiết kế**
trước — điểm nhấn, bảng màu, typography và định hướng phong cách — rồi dựng một
file `.html` độc lập duy nhất theo đúng các token đó.

<img src="docs/assets/readme/html-restyle-motion.webp" alt="Ảnh tua nhanh GenOffice HTML đổi phong cách trang landing Lumen: một yêu cầu Restyle trong panel biến trang Midnight Studio tối màu thành phiên bản Solar Daybreak ấm áp, trong khi mọi mục và nội dung đều giữ nguyên" width="100%">

<table>
<tr>
<td width="50%"><img src="docs/assets/readme/html-ai.webp" alt="GenOffice HTML: trang landing cho đèn bàn năng lượng mặt trời theo phong cách Midnight Studio tối màu, hiển thị trong xem trước trực tiếp với panel AI tóm tắt trang vừa dựng"></td>
<td width="50%"><img src="docs/assets/readme/html-restyle.webp" alt="Vẫn trang landing Lumen đó được AI đổi sang phong cách Solar Daybreak ấm áp: nền giấy, tiêu đề serif và điểm nhấn cam, mọi mục và nội dung được giữ nguyên"></td>
</tr>
<tr>
<td><b>Dựng từ một prompt</b> — hero ấn tượng, thẻ tính năng, bảng giá và form chờ cho Lumen, dựng theo phong cách Midnight Studio. Nhấp vào bất kỳ phần tử nào để đổi kiểu, nhấp đúp để sửa text, hoặc chuyển sang chế độ xem mã nguồn CodeMirror.</td>
<td><b>Cùng thiết kế, diện mạo mới</b> — một yêu cầu <b>Restyle</b> đổi các token của brief và trang web theo ngay: giấy ấm, serif kiểu biên tập, điểm nhấn cam nắng, không viết lại gì cả. Trình chiếu toàn màn hình, hoặc xuất ra PDF hay tài liệu Word chỉnh sửa được.</td>
</tr>
</table>
<table>
<tr>
<td width="50%"><img src="docs/assets/readme/html-dashboard.webp" alt="GenOffice HTML: UI dashboard cá nhân cho designer freelance theo phong cách vải lanh ấm áp, với thanh điều hướng trái, lời chào serif và bốn thẻ chỉ số"></td>
<td width="50%"><img src="docs/assets/readme/html-report.webp" alt="GenOffice HTML: báo cáo dữ liệu thị trường xe điện theo phong cách báo khổ lớn, với tên báo serif, con số tiêu đề 17,3 triệu và hàng số liệu"></td>
</tr>
<tr>
<td><b>Mockup UI</b> — mẫu "dashboard cá nhân" biến persona thành layout hoạt động được: thanh điều hướng trái, lời chào, sparkline giờ billable, thẻ hoá đơn và thẻ hiệu suất — toàn bộ là HTML thật, đưa cho developer dùng ngay được.</td>
<td><b>Kể chuyện bằng dữ liệu</b> — mẫu "báo cáo dữ liệu" dựng tờ báo khổ lớn kiểu biên tập: tên báo serif, một con số tiêu đề, hàng số liệu ngăn bằng đường kẻ, biểu đồ SVG nhúng và ghi chú phương pháp.</td>
</tr>
</table>

### 6 · Markdown — trình soạn block trên `.md` thuần, có Ask AI

<table>
<tr>
<td width="50%"><img src="docs/assets/readme/markdown-ai.webp" alt="GenOffice Markdown: một đoạn được chọn hiển thị popover Ask AI với lệnh đã gõ và các gợi ý như Polish, Make more concise, Expand và Fix grammar, cùng nút Send now và Add to queue"></td>
<td width="50%"><img src="docs/assets/readme/markdown-render.webp" alt="GenOffice Markdown hiển thị tài liệu ghi chú ra mắt với bảng, sơ đồ Mermaid và danh sách việc cần làm, với các prompt gợi ý của panel AI bên trái"></td>
</tr>
<tr>
<td><b>Hỏi AI về đoạn đã chọn</b> — chọn bất kỳ đoạn nào và chip <b>Ask AI</b> hiện ra: gõ lệnh hoặc chọn gợi ý, gửi ngay, hoặc xếp hàng nhiều chỉnh sửa neo vị trí rồi chạy một lượt. Mục này có trong mọi app.</td>
<td><b>Hiển thị đẹp, lưu Markdown thuần</b> — heading, danh sách, bảng, ảnh, khối mã và sơ đồ Mermaid trong trình soạn block Tiptap, ghi lại thành <code>.md</code> thuần, kèm xuất <b>Markdown → Word</b> hoàn toàn cục bộ.</td>
</tr>
</table>
</tr>
</table>

### 7 · Tìm kiếm — tìm file trả lời đúng câu hỏi, với TypeSafe Jev

Mọi file trong thư mục làm việc của bạn đều được index ngay trên thiết bị: tên
file, thư mục và nội dung trích xuất từ các file Word, Excel, PowerPoint, PDF,
Markdown và HTML, nằm trong một index full-text SQLite có khả năng tách từ
CJK. Bật **Jev search reranking** và 20 kết quả local đứng đầu sẽ được
[TypeSafe Jev](https://typesafe.ai/blog/introducing-system-one-models-and-jev),
model System One trả về một điểm relevance đã hiệu chuẩn cho mỗi tài liệu
trong một lần gọi duy nhất thay vì sinh văn bản, chấm điểm. Danh sách được sắp
xếp lại theo điểm đó; nếu lệnh gọi thất bại hoặc timeout, thứ tự local được
giữ nguyên.

<img src="docs/assets/readme/search-jev-motion.webp" alt="Bản ghi màn hình của màn hình chính GenOffice: gõ laptop refresh policy liệt kê chính sách browser-cache, kế hoạch brand-refresh và lịch dashboard-refresh lên trước trong khi tài liệu tiêu chuẩn thiết bị đứng cuối; trang Settings hiển thị Jev search reranking đã bật trong mục AI Media & Search với endpoint TypeSafe; cùng một truy vấn sau đó đưa tài liệu tiêu chuẩn thiết bị lên đầu với huy hiệu Jev bên cạnh số lượng kết quả" width="100%">

<table>
<tr>
<td width="50%"><img src="docs/assets/readme/search-jev-before-after.webp" alt="Hai danh sách kết quả cho truy vấn laptop refresh policy đặt cạnh nhau: không có Jev, lịch dashboard-refresh, kế hoạch brand-refresh và chính sách browser-cache refresh đứng đầu còn tài liệu tiêu chuẩn thiết bị của công ty đứng thứ năm; có Jev, tài liệu tiêu chuẩn thiết bị — tài liệu nêu chu kỳ thay thế laptop ba năm — đứng đầu"></td>
<td width="50%"><img src="docs/assets/readme/search-jev-settings.webp" alt="GenOffice Settings, trang AI Media & Search: khối Local file search với công tắc Jev search reranking, lựa chọn endpoint giữa OpenRouter và TypeSafe, và ô nhập API key"></td>
</tr>
<tr>
<td><b>Cùng một cụm từ, câu trả lời khác nhau</b> — "laptop refresh policy" khớp từng chữ với chính sách browser-cache refresh, kế hoạch brand-refresh và lịch dashboard-refresh, nên xếp hạng full-text đặt chúng lên trước. Jev đọc các đoạn trích và đưa tài liệu tiêu chuẩn thiết bị, tài liệu nêu chu kỳ thay thế ba năm, lên đầu. Huy hiệu <b>Jev</b> bên cạnh số lượng kết quả cho biết khi nào thứ tự đến từ model.</td>
<td><b>Tắt mặc định, chỉ cần một công tắc để bật</b> — Settings → AI Media & Search → Local file search. Chọn OpenRouter hoặc TypeSafe trực tiếp, dán key, bấm Test connection. Chỉ khi công tắc được bật, các đoạn trích của kết quả đứng đầu mới rời khỏi thiết bị; bản thân index thì không bao giờ.</td>
</tr>
</table>

### 8 · CLI — coding agent của bạn điều khiển GenOffice, ngay trên máy của bạn

GenOffice đi kèm dòng lệnh `genoffice` và một agent skill. Cài skill xong,
Claude Code, Codex, Cursor, Gemini CLI, GitHub Copilot, OpenCode hay Windsurf
đều có thể tạo, chuyển đổi, đọc và sửa file Office thật bằng chính các engine
như trong app, mà không cần mở cửa sổ nào.

<img src="docs/assets/readme/cli-deck-in-app.webp" alt="GenOffice Slides hiển thị deck Hệ Mặt Trời tám slide do coding agent dựng qua dòng lệnh genoffice: slide bìa trên canvas, tám thumbnail bên trái và panel AI đang mở" width="100%">

<table>
<tr>
<td width="50%"><img src="docs/assets/readme/cli-slides-grid.webp" alt="Tám slide đã render của deck Hệ Mặt Trời xếp cạnh nhau: bìa, dòng thời gian khám phá, bốn con số nổi bật, biểu đồ cột đường kính các hành tinh, các hành tinh đá đối đầu với các hành tinh khổng lồ, con số hero 99,8% của Mặt Trời, lưới bốn hành tinh khổng lồ và phần kết luận"></td>
<td width="50%"><img src="docs/assets/readme/cli-integrations.webp" alt="GenOffice Settings, trang Integrations: skill genoffice đã cài vào Claude Code, với các nút Install bên cạnh Codex và Cursor"></td>
</tr>
<tr>
<td><b>Một prompt gửi cho agent</b> — "Build an eight-slide deck about the Solar System." Agent đọc skill, viết style sheet, dàn ý và một page spec cho mỗi slide, sinh hai tấm ảnh bằng <code>genoffice image</code>, và để <code>genoffice slides check</code> loại bỏ mọi thứ bị tràn hoặc chồng lấn trước khi <code>genoffice create</code> lắp ráp file <code>.pptx</code> còn <code>slides render</code> trả về một ảnh PNG cho mỗi slide để bạn xem.</td>
<td><b>Cài một lần, từ Settings → Integrations</b> — GenOffice liệt kê các coding agent tìm thấy trên máy này và ghi skill vào từng agent bạn chọn. Hoặc tải skill dưới dạng zip, hoặc chạy <code>npx skills add quyen2867/genoffice</code>. Các lệnh và toàn bộ workflow xem tại <a href="#command-line-and-agent-skill">Dòng lệnh và agent skill</a>.</td>
</tr>
</table>

### 9 · MCP — cùng bộ công cụ đó, qua Model Context Protocol

Mọi lệnh `genoffice` đều đồng thời là một MCP tool. Claude Code, Claude
Desktop, Cursor và bất kỳ MCP client nào khác đều có thể tự khởi động
`genoffice mcp`, không cần cài skill, không cần mở cửa sổ, và nhận được 29
tool cùng các tài liệu tham khảo op dưới dạng resource. Một server HTTP thứ
hai chạy trong app cho phép agent dựng tài liệu Word ngay trong tab editor
hiển thị trước mắt bạn.

<img src="docs/assets/readme/mcp-deck-motion.webp" alt="Timelapse Claude Code dựng bản briefing nhà đầu tư về năng lượng tái tạo gồm tám slide qua genoffice MCP server: nó tìm số liệu và ảnh, kiểm tra từng ảnh ứng viên bằng media, deck_start viết style sheet và dàn ý, deck_page thêm từng slide đã kiểm tra một, deck_build lắp ráp file .pptx và slides_render trả về hình ảnh của từng slide; deck hoàn chỉnh sau đó mở ra trong GenOffice Slides" width="100%">

<table>
<tr>
<td width="50%"><img src="docs/assets/readme/mcp-deck-in-app.webp" alt="GenOffice Slides hiển thị deck Renewable Energy 2026 tám slide do Claude Code dựng qua genoffice MCP server: slide bìa với ảnh trang trại gió trên canvas và tám thumbnail bên trái"></td>
<td width="50%"><img src="docs/assets/readme/mcp-integrations.webp" alt="GenOffice Settings, trang Integrations, phần MCP: lệnh claude mcp add một dòng cho Claude Code, khối JSON cho Cursor, Claude Desktop và các MCP client khác, cùng tùy chọn local HTTP server bên dưới"></td>
</tr>
<tr>
<td><b>Một prompt, 38 lần gọi tool, không cần shell</b> — "Build an eight-slide investor briefing about renewable energy in 2026, with a real photo on the cover and wherever a photo helps." Agent lấy số liệu và ảnh bằng <code>search</code>, hỏi <code>media</code> xem từng ảnh ứng viên có phải ảnh chụp thật không, gọi <code>deck_start</code> với style sheet và dàn ý, rồi <code>deck_page</code> một lần cho mỗi slide; mỗi trang đều được đối chiếu với dàn ý và bảng màu trước khi giữ lại, <code>deck_build</code> lắp ráp file <code>.pptx</code>, <code>slides_audit</code> kiểm tra tràn nội dung, <code>slides_render</code> trả về một ảnh PNG cho mỗi slide dưới dạng image content để model xem được, và <code>deck_replace</code> sửa lại ba trang nó chưa ưng.</td>
<td><b>Kết nối một lần, từ Settings → Integrations</b> — copy dòng <code>claude mcp add</code> cho Claude Code, hoặc khối JSON cho Cursor, Claude Desktop hay bất kỳ MCP client nào. Tùy chọn B bật local HTTP server cho Word editor hiển thị. Cả hai đều được mô tả trong <a href="#mcp-server">MCP server</a>.</td>
</tr>
</table>

## Vì sao chọn GenOffice

- **Mã nguồn mở**, Apache-2.0, phát triển công khai trên GitHub.
- **Chạy trên máy của bạn.** App native cho macOS, Windows và Linux; file nằm
  trên ổ đĩa của bạn và mọi thao tác sửa, lưu, chuyển đổi đều diễn ra trên máy
  bạn.
- **File Office thật.** `.docx`, `.xlsx` và `.pptx` chuẩn native, bảo toàn
  từng byte: những phần file bạn không đụng tới được copy nguyên vẹn như cũ.
- **AI sửa trực tiếp tài liệu.** Tracked changes trong Docs, công thức và
  biểu đồ live trong Sheets, slide vẽ thẳng lên canvas, mỗi lượt AI là một
  snapshot có thể quay lại.
- **Model của bạn, key của bạn.** Đăng nhập bằng Genspark, hoặc tự mang key
  cho Claude, OpenAI, Gemini, DeepSeek và nhiều hơn nữa — kể cả server local
  và mọi endpoint tương thích OpenAI.
- **PDF làm cho đàng hoàng.** Sửa chữ ngay trong trang, chuyển PDF sang Word,
  Excel hoặc PowerPoint ngay trên máy, kèm OCR hệ thống cho file scan.
- **Cả Markdown và HTML nữa**, với cùng panel AI và xuất Word ngay trên máy.
- **Tìm kiếm ra câu trả lời, không chỉ ra từ khóa.** Tìm full-text trên mọi
  tài liệu trong thư mục của bạn, index ngay trên thiết bị, tùy chọn rerank
  bằng TypeSafe Jev — model đánh giá System One.
- **Viết script được.** Dòng lệnh `genoffice`, agent skill và MCP server đặt
  mọi engine phục vụ Claude Code, Claude Desktop, Codex, Cursor và các agent
  khác — vẫn ngay trên máy bạn.
- **Miễn phí**, cho cá nhân lẫn đội nhóm.

## Các backend AI

**Đăng nhập bằng Genspark** là không cần cấu hình gì thêm: các lệnh gọi model
đi qua proxy Genspark (các họ Claude, GPT và Gemini), còn các agent có sẵn tìm
kiếm web và ảnh, sinh ảnh, phân tích ảnh/âm thanh/video.

**Hoặc tự mang key của bạn.** Settings → AI liệt kê Claude, OpenAI, Gemini,
DeepSeek, Kimi, GLM, Qwen, Doubao, MiniMax, Grok, Mistral, OpenRouter, Requesty, Opper
và OpenCode Zen/Go, kèm một slot tùy chỉnh cho mọi endpoint tương thích OpenAI
(base URL + key), bao gồm cả server model local. Tìm kiếm và media có provider
riêng cho từng năng lực trong mục **AI Media & Search**: Serper, Tavily hoặc
Parallel cho tìm kiếm web; OpenAI, Gemini, Doubao/Seedream, GLM, Grok, Qwen,
MiniMax hoặc mọi endpoint ảnh tương thích OpenAI cho sinh ảnh và phân tích
ảnh/video; cộng thêm DeepSeek V4.1 Flash cho phân tích ảnh.

**TypeSafe Jev** rerank tính năng tìm file trên màn hình chính. Trong **AI Media
& Search → Local file search**, bật Jev search reranking và chọn endpoint:
[OpenRouter](https://openrouter.ai/typesafe) (model `typesafe/jev-1.13`) hoặc
API của chính TypeSafe. Key chỉ được lưu trên thiết bị này. Mặc định tắt; khi
bật, chỉ các đoạn trích của 20 kết quả local đứng đầu được gửi đi chấm điểm,
không có gì khác rời khỏi máy.

**Parallel** chạy được mà không cần tài khoản: Search MCP miễn phí (giới hạn
tốc độ) của nó là công cụ tìm kiếm web mặc định mỗi khi chưa đăng nhập Genspark
hay cấu hình search key, và nó chạy trước cả DuckDuckGo scrape. Chọn Parallel
trong mục Web search và nhập key [Parallel](https://platform.parallel.ai/) để
dùng Search API thay thế.

Toàn bộ bộ app đi kèm theme sáng, tối và theo hệ thống. Theme chỉ thay đổi
những gì hiển thị trên màn hình: file xuất, bản in và file đã lưu luôn giữ
nguyên màu gốc của tài liệu.

## Dòng lệnh và agent skill

Mọi việc app làm được với một file, dòng lệnh `genoffice` đều làm được từ
terminal: kiểm tra, chuyển đổi, tạo, đọc và sửa Word, Excel, PowerPoint, PDF,
Markdown và HTML trên cùng các engine, chạy headless. Nó được cài kèm
GenOffice, không cần runtime riêng, và không bao giờ gửi tài liệu đi đâu. Kết
hợp với **agent skill** đi kèm, nó biến coding agent thành một trợ lý tài liệu
tạo ra file Office thật thay vì bản Markdown gần đúng.

**Tương thích với:** Claude Code, Codex, Cursor, Gemini CLI, GitHub Copilot,
OpenCode và Windsurf ngay khi mở hộp, mọi agent khác đọc được skill, và — thông
qua [MCP server](#mcp-server) — Claude Desktop cùng mọi MCP client.

### Cài đặt skill

| Cách làm                                  | Điều gì xảy ra                                                                                                                                                                 |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Settings → Integrations** trong app     | Liệt kê các agent tìm thấy trên máy này; một cú click ghi skill vào từng agent bạn chọn. Nút **Update** xuất hiện khi bản phát hành GenOffice mới mang theo skill mới hơn.   |
| **Download as zip** trên cùng trang đó    | Định dạng mà claude.ai, các app Claude desktop và các trợ lý khác chấp nhận khi upload skill.                                                                                 |
| `npx skills add quyen2867/genoffice`      | Cài từ repo này vào mọi agent tương thích skill.                                                                                                                              |

Sau đó mở một đoạn chat mới và yêu cầu một tài liệu. Skill dạy agent khi nào
nên dùng `genoffice`, cách đọc file trước khi sửa, và cách tự kiểm tra thành
quả của mình.

### Bắt đầu nhanh từ terminal

```bash
genoffice --version
genoffice info report.docx --json                  # headings and blocks; or sheets, slides, pages
genoffice convert report.md --to pdf               # md/html/docx/xlsx/pptx → pdf, pdf → docx/xlsx/pptx, …
genoffice create --type docx --from notes.md --out notes.docx
genoffice create --type xlsx --from table.json --out sales.xlsx   # "=SUM(B2:B9)" cells stay live formulas
genoffice docs read report.docx --range 0-9 --json # then `docs apply --ops edits.json` edits in place
genoffice render report.docx --out shots/          # one PNG per page, to look at what you made
genoffice open sales.xlsx                          # hand the result to the editor
```

Mỗi lệnh in ra một dòng tóm tắt, hoặc một object JSON duy nhất với `--json`.
Các thao tác sửa là atomic: một op bị từ chối sẽ để file nguyên vẹn và trả về
lỗi có hướng dẫn. `genoffice help` liệt kê toàn bộ lệnh hiện có; tài liệu đầy
đủ xem tại [packages/cli/README.md](packages/cli/README.md).

### Agent thực sự chạy những gì
Deck Hệ Mặt Trời trong [demo](#demo) chỉ cần một prompt trong Claude Code.
Đằng sau nó, agent làm theo quy trình từng bước của skill và CLI kiểm tra
từng bước trước khi bước tiếp theo bắt đầu:

```bash
genoffice capabilities --json                        # which cloud tools GenOffice has configured
genoffice guide slides design                        # the deck workflow and layout library
genoffice image "the eight planets in a row …" --aspect 16:9 --out deck/assets/cover.jpg
genoffice slides check deck/outline.json --json      # 8 pages, no findings
genoffice slides check deck/pages/01.json --json     # builds one slide, audits overflow and overlap
…                                                    # one page file per slide, fixed until each check is clean
genoffice create --type pptx --spec deck/pages --outline deck/outline.json --out deck/solar-system.pptx --json
genoffice slides render deck/solar-system.pptx --out deck/shots --json
genoffice slides audit deck/solar-system.pptx --json    # 8 slides, no layout issues
genoffice slides replace deck/solar-system.pptx --slide 4 --spec deck/pages/05.json --json
genoffice open deck/solar-system.pptx
```

Không có lời gọi model nào diễn ra bên trong `genoffice`: agent lo phần tư duy,
CLI lo phần dựng và kiểm tra, và kết quả mở ra trong GenOffice hoặc PowerPoint
như một file `.pptx` bình thường.

### Máy chủ MCP

Các lệnh tương tự cũng có sẵn dưới dạng tool
[Model Context Protocol](https://modelcontextprotocol.io), dành cho các
assistant không chạy được terminal hoặc bạn không muốn cấp terminal cho chúng.
Có hai cách dùng, cả hai đều có đoạn mã copy-paste sẵn trong
**Settings → Integrations → MCP**:

| Cách                                  | Mô tả                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **A · `genoffice mcp`** (khuyên dùng) | Một máy chủ stdio do chính assistant khởi động; không cần mở GenOffice. Một tool cho mỗi lệnh (`info`, `convert`, `create_docx`, `create_xlsx`, `create_pptx`, `create_pdf`, `docs_read` / `docs_apply` / `docs_check`, `sheet_*`, `slides_*`, `render`, `guide`, `search`, `image`, `media`, `open`) cộng thêm luồng dựng deck từng bước `deck_start` → `deck_page` → `deck_build` → `deck_replace`. Ops, spec và Markdown được truyền nội tuyến (inline), nên client không có hệ thống file vẫn dùng được. |
| **B · Máy chủ HTTP nội bộ**           | Chạy bên trong app GenOffice tại `http://127.0.0.1:3093/mcp` (Streamable HTTP, kèm SSE cũ). Các tool của nó điều khiển một tab soạn thảo Word nhìn thấy được: `create_session`, `insert_content`, `replace_blocks`, `apply_ops`, `read_document`, `save_session`, và bạn nhìn thấy tài liệu dần thành hình. Tắt mặc định; bật lên trong cùng panel cài đặt.                                                                                                                                                |
| **C · `genoffice mcp --http`**        | Bộ tool stdio dưới dạng máy chủ Streamable HTTP cho các client trên máy khác: container, sandbox, máy dùng chung trong mạng của bạn. File đi kèm theo các lời gọi: `PUT /files/<name>` tải lên một file và trả về URL, mọi tham số `file` đều nhận URL http(s), và tool nào ghi ra file sẽ trả lại dưới dạng URL tải xuống, kèm theo (khi file nhỏ) dữ liệu bytes dưới dạng MCP resource. `--host 0.0.0.0` mở ra mạng, `--token` bảo vệ nó.                                                          |

```bash
# Claude Code
claude mcp add --transport stdio genoffice -- genoffice mcp
```

```jsonc
// Cursor, Claude Desktop or any other MCP client
{ "mcpServers": { "genoffice": { "command": "genoffice", "args": ["mcp"] } } }
```

```bash
# On the machine that has GenOffice (private network; add --token for a shared box)
genoffice mcp --http 3093 --host 0.0.0.0 --token "$GENOFFICE_MCP_TOKEN"

# From the client: upload, then use the URL wherever a tool takes a file
curl -T report.docx -H "Authorization: Bearer $GENOFFICE_MCP_TOKEN" http://server:3093/files/
#   → { "url": "http://server:3093/files/<id>/report.docx", ... }
#   docs_read({ "file": "http://server:3093/files/<id>/report.docx" })
#   docs_apply(...) → output_url, downloadable with curl -o
```

Qua HTTP, mỗi session được cấp một thư mục scratch riêng, đường dẫn tương đối
và thư mục deck được giải quyết trong đó, `open` không được cung cấp, và khi
chưa đặt `GENOFFICE_ALLOWED_ROOTS` thì các tool không thể ra khỏi kho file của
chính server. `render`, `convert` sang PDF và `create_pdf` vẫn khởi động một
tiến trình GenOffice ẩn, nên máy headless cần cài sẵn app và một màn hình ảo
(`xvfb-run`).

`genoffice` ở đây là CLI đi kèm trong app (trên macOS là
`/Applications/GenOffice.app/Contents/Resources/cli/genoffice`; panel cài đặt in
ra đường dẫn chính xác cho bản cài của bạn). Server mang sẵn hướng dẫn quy
trình và công khai tài liệu op dưới dạng resource `genoffice://guide/*`, nên
không cần skill; skill và MCP server có thể cùng tồn tại và assistant sẽ chọn
một trong hai. Các tính năng cloud (`search`, `image`, `media`) vẫn đi qua
provider đã cấu hình trong GenOffice; mọi thứ khác chạy cục bộ, và
`GENOFFICE_ALLOWED_ROOTS` giới hạn mọi tool trong các thư mục bạn liệt kê.

Deck năng lượng tái tạo trong [demo](#demo) là hình ảnh một prompt trong
Claude Code chỉ gắn mỗi MCP server `genoffice` nhìn từ phía giao thức:

```text
capabilities · guide(slides, spec) · guide(slides, design)
search(query) ×4                         → IEA, BNEF and IRENA figures for the slides
search(query, images) ×7 · media(url, ask) ×7
                                         → candidate photos, each one checked to be a real photograph
deck_start(dir, style, outline)          → outline checked: 8 pages to write
deck_page(dir, 0, page) … deck_page(dir, 7, page)
                                         → each page checked against the outline and the palette; one page sent again
deck_build(dir, out)                     → renewables-2026.pptx, no image failures
slides_audit(file) · slides_render(file, out)
                                         → no layout findings; 8 PNGs come back as image content
deck_replace(dir, n, page) ×3 · slides_render(file, out)
                                         → three pages fixed after looking at the renders
```

Ba mươi tám lời gọi, khoảng mười ba phút, và assistant không hề chạm vào
shell: số liệu, ảnh, hướng dẫn, kết quả kiểm tra và bản render đều đi qua dưới
dạng kết quả MCP tool. Chỉ `search` và `media` rời khỏi máy, tới provider đã
cấu hình trong GenOffice.

## Tải xuống

| Nền tảng                             | Yêu cầu                                              | Tải xuống                                                                                      |
| ------------------------------------ | ----------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| **macOS** — Apple Silicon (arm64)    | macOS 11+                                             | [`.dmg` (arm64) mới nhất](https://github.com/quyen2867/genoffice/releases/latest)         |
| **macOS** — Intel (x64)              | macOS 11+                                             | [`.dmg` (x64) mới nhất](https://github.com/quyen2867/genoffice/releases/latest)           |
| **Windows** (x64, đa số PC)          | Windows 10+, Intel/AMD                                | [Trình cài đặt `-x64.exe` mới nhất](https://github.com/quyen2867/genoffice/releases/latest)   |
| **Windows** trên Arm (ARM64)         | Windows 11 trên Arm (Snapdragon X và tương tự)        | [Trình cài đặt `-arm64.exe` mới nhất](https://github.com/quyen2867/genoffice/releases/latest) |
| **Linux** — Debian / Ubuntu          | x86_64, glibc 2.34+ (Ubuntu 22.04 trở lên)            | [`.deb` mới nhất](https://github.com/quyen2867/genoffice/releases/latest)                 |
| **Linux** — Fedora / RHEL / openSUSE | x86_64, glibc 2.34+ (Fedora 35+, RHEL 9+, Leap 15.6+) | [`.rpm` mới nhất](https://github.com/quyen2867/genoffice/releases/latest)                 |
| **Linux** — các bản phân phối khác   | x86_64, glibc 2.34+, FUSE 2                           | [`.AppImage` mới nhất](https://github.com/quyen2867/genoffice/releases/latest)            |

Mọi bản build đều từ nhánh `main`; trình cài đặt macOS và Windows đã được ký.
Các phiên bản cũ hơn có trên trang [Releases](https://github.com/quyen2867/genoffice/releases).

<details>
<summary><b>Cài đặt trên Linux</b></summary>

Gói deb cài bằng apt — nó tự kéo các phụ thuộc và thêm GenOffice vào menu ứng
dụng:

```bash
sudo apt install ./genoffice_<version>_amd64.deb
```

Trên Fedora / họ RHEL / openSUSE, cài gói rpm thay thế:

```bash
sudo dnf install ./genoffice-<version>.x86_64.rpm     # Fedora / RHEL family
sudo zypper install ./genoffice-<version>.x86_64.rpm  # openSUSE
```

AppImage chạy tại chỗ: cài runtime FUSE 2
(`sudo apt install libfuse2`; trên Ubuntu 24.04 gói tên là `libfuse2t64`),
cấp quyền thực thi cho file, rồi chạy:

```bash
chmod +x GenOffice-<version>.AppImage
./GenOffice-<version>.AppImage
```

</details>

## Cách hoạt động

Bảy app Electron — Docs, Sheets, Slides, PDF, Markdown, HTML và shell dạng
tab — dùng chung một lớp engine gồm các package TypeScript thuần túy cộng một
sidecar Rust cho `.xlsx`. File gốc luôn là nguồn chân lý: các chỉnh sửa được
áp dụng dưới dạng patch hẹp, và mọi thứ editor không chạm tới đều nguyên vẹn
sau một vòng đi-về.

```
open docx ─► archive original by hash (never touched)
          ─► parse word/document.xml into a block tree, each block anchored to its original XML
          ─► Tiptap editor (manual + AI editing, dirty tracking)
save      ─► dirty blocks → OOXML fragments (referencing existing styles only)
          ─► splice into the original document.xml; untouched blocks keep their bytes
          ─► repack the zip; every other entry is copied byte-for-byte
```

Tour chi tiết từng package (engine docx/pptx, `pdf2docx`, `html2docx`, agent
core và các provider) nằm trong [CONTRIBUTING.md](CONTRIBUTING.md#engine-packages).

## Phát triển

```bash
npm install
npm run fixtures     # generate test .docx fixtures
npm test             # engine + app unit tests (docs/sheets/slides need no display)
npm run typecheck    # tsc --noEmit across every workspace
npm run dev          # all six editors + shell against Vite dev servers
npm run dev:docs     # a single app (same pattern works per workspace)
npm run dist:mac     # package macOS dmg (regenerates third-party notices)
npm run dist:win     # package Windows nsis installer
npm run dist:linux   # đóng gói Linux AppImage + deb + rpm
```

App bảng tính cần thêm Rust toolchain cho sidecar xlsx
(`cargo` có trong PATH); lệnh `npm run build -w @genoffice/sheets` sẽ tự
động biên dịch nó. Xem [CONTRIBUTING.md](CONTRIBUTING.md) để biết các kiểm
tra bắt buộc cho mọi thay đổi và cách gửi pull request.

## Cộng đồng

GenOffice đang được phát triển tích cực và phản hồi của bạn giúp định hình nó.

- **Báo lỗi hoặc đề xuất tính năng** tại
  [GitHub Issues](https://github.com/quyen2867/genoffice/issues).
- **Tham gia nhóm chat GenOffice** trên
  [GenTeam](https://genoffice.ai/join) để trò chuyện với đội ngũ và cộng đồng.
- **Theo dõi [@merrickbuilds](https://x.com/merrickbuilds) trên X** để xem
  ghi chú phát hành, demo và những gì sắp ra mắt.
- **Star repo** nếu GenOffice hữu ích với bạn — đó là cách ủng hộ dự án tốt nhất.

## Câu hỏi thường gặp

<details>
<summary><b>GenOffice có miễn phí không?</b></summary>

Có. GenOffice miễn phí và mã nguồn mở theo giấy phép Apache-2.0 — không
dùng thử, không có gói trả phí cho các ứng dụng.

</details>

<details>
<summary><b>GenOffice có mở được file Microsoft Word, Excel và PowerPoint không?</b></summary>

Có. GenOffice mở và lưu file `.docx`, `.xlsx` và `.pptx` nguyên bản.
Việc lưu giữ nguyên từng byte: những phần file bạn không động đến sẽ được
ghi lại y hệt byte-for-byte, nên tài liệu vẫn dùng bình thường trong Microsoft Office.

</details>

<details>
<summary><b>GenOffice có hoạt động ngoại tuyến không?</b></summary>

Soạn thảo tài liệu hoàn toàn cục bộ — file không bao giờ rời khỏi máy của bạn
để mở, chỉnh sửa, lưu hay chuyển đổi. Các tính năng AI (agent, tìm kiếm, công
cụ hình ảnh) cần kết nối mạng, dùng tài khoản Genspark đăng nhập sẵn không cần
key, hoặc API key của chính bạn.

</details>

<details>
<summary><b>GenOffice có chỉnh sửa được file PDF không?</b></summary>

Có — chỉnh sửa văn bản và hình ảnh PDF thật sự, ghi lại trực tiếp luồng nội
dung của trang mà vẫn giữ nguyên font gốc, không phải kiểu chú thích che phủ.

</details>

<details>
<summary><b>GenOffice có chuyển PDF sang Word, Excel hoặc PowerPoint được không?</b></summary>

Có — hoàn toàn trên thiết bị: trích xuất PDFium ở cấp độ ký tự kết hợp phân
tích bố cục theo hình học, không qua dịch vụ đám mây, không tải lên. Trang
quét scan cũng được hỗ trợ: trên macOS và Windows, OCR của hệ thống sẽ đọc
chúng, nên chúng được chuyển thành văn bản chỉnh sửa được thay vì ảnh trang.

</details>

<details>
<summary><b>Tôi có thể dùng model AI hoặc API key của riêng mình không?</b></summary>

Có. Ngoài đăng nhập Genspark không cần key, GenOffice hỗ trợ dùng key của
riêng bạn cho Claude, OpenAI, Gemini, DeepSeek, Kimi, GLM, Qwen, Doubao, MiniMax,
Grok, Mistral, OpenRouter, Requesty, Opper và OpenCode Zen/Go, cộng mọi
endpoint tương thích OpenAI — kể cả server model chạy cục bộ. Tìm kiếm, tạo
ảnh và phân tích ảnh/video dùng key riêng trong mục Settings → AI Media & Search.

</details>

<details>
<summary><b>GenOffice có chuyển HTML sang Word được không?</b></summary>

Có — chức năng Export as Word trong app HTML tạo ra file `.docx` chỉnh sửa
được hoàn toàn trên thiết bị. Trang được render trong Chromium tích hợp rồi
rút gọn thành cấu trúc Word thật: tiêu đề, đoạn văn, danh sách, bảng, thẻ,
hàng KPI, trường biểu mẫu và nền trang; chỉ những yếu tố không có đối ứng
trong Word (biểu đồ, icon, hộp trang trí) mới được nhúng dưới dạng ảnh.

</details>

<details>
<summary><b>Tôi có thể điều khiển GenOffice từ Claude Code, Codex, Cursor hoặc script không?</b></summary>

Có. GenOffice cài sẵn lệnh dòng lệnh `genoffice` chạy các engine tương tự ở
chế độ headless: xem, chuyển đổi, tạo, đọc và chỉnh sửa tài liệu từ terminal
hoặc script, với đầu ra `--json` cho chương trình xử lý. Skill agent đi kèm
hướng dẫn Claude Code, Codex, Cursor, Gemini CLI, GitHub Copilot, OpenCode và
Windsurf cách dùng nó; cài đặt từ **Settings → Integrations**. Xem
[Command line and agent skill](#command-line-and-agent-skill).

</details>

<details>
<summary><b>GenOffice có thu thập dữ liệu nào không?</b></summary>

Bản dựng chính thức gửi một lượng giới hạn phân tích sử dụng theo mặc định,
và bạn có thể tắt báo cáo bất cứ lúc nào trong Settings → General. Phân tích
không bao giờ gửi nội dung tài liệu, tên file, đường dẫn file, danh tính tài
khoản hay địa chỉ email. Xem [GenOffice Privacy](PRIVACY.md) để biết đầy đủ
thông tin về các sự kiện và dữ liệu được thu thập.

</details>

## Bảo mật

Xem [SECURITY.md](SECURITY.md) để biết tư thế bảo mật của tiến trình (sandbox
renderer, kiểm tra IPC, chặn liên kết ngoài) và các mô hình đe dọa đối với
nội dung do AI tạo ra.

## Ghi nhận

GenOffice không thể ra đời nếu thiếu các dự án mã nguồn mở này:

- [Electron](https://www.electronjs.org/) — runtime desktop cho mọi app.
- [Univer](https://github.com/dream-num/univer) (Apache-2.0) — lõi UI bảng
  tính mà Sheets mở rộng.
- [PDFium](https://pdfium.googlesource.com/pdfium/) (BSD-3-Clause, đóng gói qua
  [@embedpdf/pdfium](https://github.com/embedpdf/embed-pdf-viewer)) — engine
  luồng nội dung đứng sau khả năng chỉnh sửa văn bản và hình ảnh PDF thật.
- [pdf.js](https://github.com/mozilla/pdf.js) (Apache-2.0) và
  [pdf-lib](https://github.com/Hopding/pdf-lib) (MIT) — render PDF và lắp ráp
  tài liệu.
- [Tiptap](https://tiptap.dev/) / [ProseMirror](https://prosemirror.net/) —
  trình soạn thảo khối trong Docs và Markdown.
- [CodeMirror](https://codemirror.net/) (MIT) — trình soạn mã nguồn trong HTML.
- [Konva](https://konvajs.org/) — render canvas cho Slides và biểu đồ Sheets.
- [HarfBuzz](https://github.com/harfbuzz/harfbuzz) (wasm) — số liệu tạo hình
  văn bản cho chữ viết phức tạp.
- [calamine](https://github.com/tafia/calamine) và
  [IronCalc](https://github.com/ironcalc/IronCalc) — lớp đọc và tính toán
  của sidecar xlsx viết bằng Rust.
- [libeot](https://github.com/umanwizard/libeot) (MPL-2.0) — bộ giải mã
  MicroType Express cho font nhúng trong PowerPoint, được port sang TypeScript.
- [React](https://react.dev/) (MIT) — lớp giao diện của mọi app.
- [Mermaid](https://mermaid.js.org/) (MIT) và [KaTeX](https://katex.org/)
  (MIT) — sơ đồ và công thức toán trong Markdown và Docs.
- [opentype.js](https://opentype.js.org/) (MIT) — phân tích font để lấy số
  liệu và tra cứu glyph.
- [JSZip](https://stuk.github.io/jszip/) (MIT) và
  [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser)
  (MIT) — lớp container OOXML và XML.
- [Fluent UI System Icons](https://github.com/microsoft/fluentui-system-icons)
  (MIT) — bộ icon trên các ribbon.
- [electron-updater](https://www.electron.build/) (MIT) — cập nhật trong app.
- Font Liberation, Carlito, Caladea và Noto CJK (OFL/Apache-2.0) — font tài
  liệu đóng gói sẵn.

Lệnh `npm run notices` tái tạo bản tóm tắt giấy phép bên thứ ba đi kèm
(`tools/gen-third-party-notices.mjs`); mọi dependency runtime đều là
MIT/Apache-2.0/BSD-3-Clause/OFL.

## Giấy phép

GenOffice được cấp phép theo [Apache License 2.0](LICENSE), với một ngoại
lệ: thư mục `ee/` dành riêng cho các module doanh nghiệp trong tương lai và
chịu [GenOffice Enterprise License](ee/LICENSE).

Tên và logo GenOffice, Genspark là thương hiệu của Mainfunc, Inc.
Giấy phép Apache-2.0 không cho phép sử dụng chúng (xem mục 6); các bản fork
nên dùng thương hiệu của riêng mình.
