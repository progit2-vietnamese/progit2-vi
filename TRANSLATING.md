# Bản dịch Pro Git (Phiên bản thứ 2)

Các bản dịch được quản lý theo cách phi tập trung. Mỗi nhóm dịch thuật duy trì dự án của riêng họ. Mỗi bản dịch nằm trong kho lưu trữ riêng của nó, nhóm Pro Git chỉ cần kéo các thay đổi về và tích hợp chúng vào trang web https://git-scm.com khi đã sẵn sàng.

## Hướng dẫn chung cho việc dịch Pro Git

Pro Git là một cuốn sách về một công cụ kỹ thuật, trước khi dịc
Pro Git is a book about a technical tool, do đó việc dịch nó rất khó so với một bản dịch phi kỹ thuật.

Sau đây là các nguyên tắc để giúp bạn tiếp tục việc dịch của mình:
* Trước khi bắt đầu, hãy đọc toàn bộ cuốn sách Git Pro bằng tiếng Anh để bạn biết nội dung và quen với văn phong được sử dụng.
* Đảm bảo bạn có kiến thức làm việc tốt về git để việc giải thích các thuật ngữ kỹ thuật được tốt nhất.
* Bám sát một phong cách và định dạng chung cho bản dịch.
* Hãy nhớ đọc kỹ và hiểu những kiến thức cơ bản về [Asciidoc formatting](https://asciidoctor.org/docs/asciidoc-syntax-quick-reference/). Không tuân theo cú pháp asciidoc có thể dẫn đến các vấn đề với việc xây dựng/biên dịch các tập tin pdf, epub và html cần thiết cho cuốn sách.

## Dịch cuốn sách sang ngôn ngữ khác

### Giúp đỡ việc dịch với một dự án đã có

* Kiểm tra một dự án đã tồn tại trong bảng sau.
* Truy cập trang của dự án trên GitHub.
* Mở một báo cáo vấn đề(issue), giới thiệu bản thân và yêu cầu nơi bạn có thể giúp đỡ.

| Ngôn ngữ     | Trang GitHub     |
| :------------- | :------------- |
| Ả Rập | [progit2-ar/progit2](https://github.com/progit2-ar/progit2) |
| Belarus  | [progit/progit2-be](https://github.com/progit/progit2-be) |
| Bungari | [progit/progit2-bg](https://github.com/progit/progit2-bg) |
| Séc    | [progit-cs/progit2-cs](https://github.com/progit-cs/progit2-cs) |
| Tiếng Anh    | [progit/progit2](https://github.com/progit/progit2) |
| Tây Ban Nha    | [progit/progit2-es](https://github.com/progit/progit2-es) |
| Farsi | [progit2-fa/progit2](https://github.com/progit2-fa/progit2) |
| Pháp   | [progit/progit2-fr](https://github.com/progit/progit2-fr) |
| Đức    | [progit/progit2-de](https://github.com/progit/progit2-de) |
| Hy Lạp   | [progit2-gr/progit2](https://github.com/progit2-gr/progit2) |
| Indonesia | [progit/progit2-id](https://github.com/progit/progit2-id) |
| Italia   | [progit/progit2-it](https://github.com/progit/progit2-it) |
| Nhật Bản   | [progit/progit2-ja](https://github.com/progit/progit2-ja) |
| Hàn Quốc   | [progit/progit2-ko](https://github.com/progit/progit2-ko) |
| Macedonia | [progit2-mk/progit2](https://github.com/progit2-mk/progit2) |
| Mã Lai | [progit2-ms/progit2](https://github.com/progit2-ms/progit2) |
| Hà Lan | [progit/progit2-nl](https://github.com/progit/progit2-nl) |
| Ba Lan | [progit2-pl/progit2-pl](https://github.com/progit2-pl/progit2-pl) |
| Bồ Đào Nha (Brasil) | [progit/progit2-pt-br](https://github.com/progit/progit2-pt-br) |
| Liên Bang Nga   | [progit/progit2-ru](https://github.com/progit/progit2-ru) |
| Slovenia  | [progit/progit2-sl](https://github.com/progit/progit2-sl) |
| Serbia   | [progit/progit2-sr](https://github.com/progit/progit2-sr) |
| Thuỵ Điển  | [progit2-sv/progit2](https://github.com/progit2-sv/progit2) |
| Tagalog   | [progit2-tl/progit2](https://github.com/progit2-tl/progit2) |
| Thổ Nhĩ Kỳ   | [progit/progit2-tr](https://github.com/progit/progit2-tr) |
| Ukraina| [progit/progit2-uk](https://github.com/progit/progit2-uk) |
| Uzbek  | [progit/progit2-uz](https://github.com/progit/progit2-uz) |
| Tiếng Trung giản thể  | [progit/progit2-zh](https://github.com/progit/progit2-zh) |
| Tiếng Trung phồn thể  | [progit/progit2-zh-tw](https://github.com/progit/progit2-zh-tw) |

### Bắt đầu một bản dịch mới

Nếu không có dự án nào cho ngôn ngữ của bạn, bạn có thể bắt đầu bản dịch của riêng mình.

Bản dịch của bạn phải dựa trên phiên bản thứ 2 của cuốn sách, có [ tại đây](https://github.com/progit/progit2). Bằng cách:
 1. Chọn chính xác mã [ISO 639 code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) cho ngôn ngữ của bạn.
 1. Tạo một [GitHub organization](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/creating-a-new-organization-from-scratch), ví dụ: `progit2-[your code]` trên Github.
 1. Tạo một dự án `progit2`.
 1. Sao chép cấu trúc của progit/progit2 (dự án này) vào dự án của bạn và bắt đầu dịch.

### Cập nhật trạng thái của bản dịch

Trên https://git-scm.com, các bản dịch được chia thành ba loại. Khi bạn đã đạt đến một trong những cấp độ này, hãy liên hệ với những người bảo trì của https://git-scm.com/ để họ có thể thực hiện các thay đổi.

| Loại | Mức hoàn thành     |
| :------------- | :------------- |
| Bản dịch đã bắt đầu, |  phần giới thiệu đã dịch, không có nhiều thứ khác. |
| Bản dịch đã xong một phần | đã dịch xong 6 chương. |
| Toàn bộ bản dịch đã sẵn sàng |cuốn sách đã hoàn thành việc dịch. |

## Tích hợp liên tục với GitHub Actions

GitHub Actions là một dịch vụ [tích hợp liên tục](https://en.wikipedia.org/wiki/Continuous_integration) tích hợp với GitHub. GitHub Actions được sử dụng để đảm bảo rằng một yêu cầu kéo không phá vỡ quá trình xây dựng hoặc biên dịch. GitHub Actions cũng có thể cung cấp các phiên bản đã biên dịch của cuốn sách.
Cấu hình cho GitHub Actions được chứa trong thư mục `.github/workflows` và nếu bạn mang vào nhánh `main` của kho lưu trữ gốc, bạn sẽ nhận được chúng miễn phí.
Tuy nhiên, nếu bạn đã tạo repo bản dịch của mình bằng _forking_ repo gốc, bạn phải hoàn thành một bước bổ sung (nếu chưa fork, bạn có thể bỏ qua phần này).
GitHub giả định rằng các fork sẽ được sử dụng để đóng góp vào repo mà từ đó chúng đã được fork, vì vậy bạn sẽ phải truy cập tab "Hành động" trên repo đã chia nhánh của mình và nhấp vào nút "Tôi hiểu quy trình công việc của mình" để cho phép các hành động chạy.

## Thiết lập chuỗi xuất bản sách điện tử

Đây là nhiệm vụ kỹ thuật, vui lòng ping tới @jnavila để bắt đầu xuất bản epub.
## Ngoài Pro Git

Dịch cuốn sách là bước đầu tiên. Sau khi hoàn tất, bạn có thể xem xét việc dịch giao diện người dùng của chính Git.

Nhiệm vụ này đòi hỏi một kiến thức kỹ thuật về công cụ nhiều hơn so với sách. Hy vọng sau khi đã dịch đầy đủ nội dung cuốn sách, bạn có thể hiểu được các thuật ngữ sử dụng trong ứng dụng. Nếu bạn cần nâng cao yêu cầu về mặt kỹ thuật, xem kho lưu trữ [tại đây](https://github.com/git-l10n/git-po) và bạn chỉ cần làm theo [hướng dẫn](https://github.com/git-l10n/git-po/blob/master/po/README).

Hãy cẩn thận về điều đó

 * bạn sẽ cần sử dụng các công cụ cụ thể hơn để quản lý các tệp po bản địa hóa (chẳng hạn như chỉnh sửa chúng bằng [poedit](https://poedit.net/) và hợp nhất chúng. Bạn có thể cần phải biên dịch git để kiểm tra công việc của mình.
 * cần có kiến thức cơ bản về cách thức hoạt động của các ứng dụng dịch, điều này khác biệt đáng kể so với việc dịch sách.
 * dự án phần lõi của Git sử dụng [quy trình](https://github.com/git-l10n/git-po/blob/master/Documentation/SubmittingPatches) nghiêm ngặt hơn trong việc chấp nhận các đóng góp, hãy đảm bảo tuân thủ chúng.
