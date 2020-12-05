# ServiceAgency

პროექტის აღწერა რამდენიმე შემთხვევაში შეიცავს ისეთ დეტალებს, რომელთა იმპლენტაცია შეიძლება განხორციელდეს მრავალი სახით. ასეთ შემთხვევებში გადაწყვეტილების მიღებაში თავისუფალი ხარ და არჩევანი შენზეა დამოკიდებული. დავალებაში სურვილისამებრ შეტანილი გაუმჯობებისკენ მიმართული ინიციატივები ჩაითვლება დადებითად. დავალების გაცნობის შემდგომ გთხოვ დამიდასტურო წერილის მიღება ამ წერილზე პასუხის სახით.

 

 

სატრანსპორტო საშუალებების ცნობარი

 

ამოცანა: შექმენით სატრანსპორტო საშუალებებისცნობარის API შემდეგი ფუნქციებით:

სატრანსპორტო საშუალების დამატება/რედაქტირება/წაშლა
სატრანსპორტო საშუალებების სიის მიღება  - სწრაფი და დეტალური ძებნის მეშვეობით, paging -ისა და ordering- ის ფუნქციით
სატრანსპორტო საშუალების დეტალური ინფორმაციის მიღება იდენტიფიკატორის მეშვეობით
სატრანსპორტო საშუალების სურათის  დამატება/შეცვლა/წაშლა
სატრანსპორტო საშუალების მფლობელის დამატება/წაშლა
სატრანსპორტო საშუალების მფლობელთა სიის მიღება
 

სატრანსპორტო საშუალება უნდა შეიცავდეს ავტომატურად გენერირებულ უნიკალურ იდენტიფიკატორს, მარკას ქართულ და ლათინურ ენაზე, მოდელს ქართულ და ლათინურ ენაზე, ვინ კოდს, სატრანსპორტო ნომერს, დამზადების თარიღს, ფერის იდენტიფიკატორს, 1 საწვავის ტიპი(სამომავლოდ მრავალად მარტივად გადაკეთების პერსპექტივით), მრავალ მფლობელს(სახელი, გვარი, პირადი ნომერი), სურათს.

 

გამოყენებული ტექნოლოგიები:

ASP.NET Core,
Entity Framework Core,
Microsoft SQL/PostgreSQL
 

აუცილებელია:

პროექტი შესრულებული იყოს Clean Architecture ის გამოყენებით.
ყველა ოპერაციისა და პროექტის მთლიანობის ვალიდაცია(API მოდელების ვალიდაციისთვის სასურველი Fluent Validation ბიბლიოთეკის გამოყენება, მონაცემთა ბაზის მოდელებისთვის სასურველია Entity Framework-ის Fluent Configuration-ის გამოყენება)
შეცდომების შემთხვევაში შესაბამისი შეტყობინებების დაბრუნება და მათი მარტივად პოვნის გათვალისწინება
API Middleware-ის შექმნა შეცდომების დამუშავებისთვისა და ლოგირებისთვის
API Middleware-ის შექმნა შესაბამისი მოთხოვნის Accept-Language HTTP Header პარამეტრის შესაბამისი ლოკალიზაციის/ენის დაყენებისთვის.
საწყისი დამხმარე ცნობარი მონაცემების ინიციალიზაცია მოახდინეთ კოდით.
დოკუმენტირებისთვის გამოიყენეთ Swagger
 

სასურველია:

Repository და Unit of Work პატერნების გამოყენება.
(მიმდინარე პროექტში დასამატებელია fluent Validation,fluent Configuration და Unit of Work პატერნი,ვინაიდან საჭიროება არიყო ამ სერვისების გამოყენების. მივანიჭე ყურადღება სხვა თემებს დროის სიმცირის გამო)
