# The Unreasonable Effectiveness of Recurrent Neural Networks

https://github.com/karpathy/char-rnn

➜  rnn $ th train.lua -data_dir data/wiki -gpuid -1
➜  rnn $ th train.lua -data_dir data/wiki  -rnn_size 512 -num_layers 2 -dropout 0.5

loading data files...	
cutting off end of data so that the batches/sequences divide evenly	
reshaping tensor...	
data load done. Number of data batches in train: 11952, val: 630, test: 0	
vocab size: 119	
creating an lstm with 2 layers	
setting forget gate biases to 1 in LSTM layer 1	
setting forget gate biases to 1 in LSTM layer 2	
number of parameters in the model: 274935	
cloning rnn	
cloning criterion	
1/597600 (epoch 0.000), train_loss = 4.78552416, grad/param norm = 7.2153e-01, time/batch = 2.9597s	
2/597600 (epoch 0.000), train_loss = 4.34859693, grad/param norm = 2.3261e+00, time/batch = 2.8736s	
3/597600 (epoch 0.000), train_loss = 3.14648111, grad/param norm = 1.4727e+00, time/batch = 2.7997s	
4/597600 (epoch 0.000), train_loss = 2.74398308, grad/param norm = 9.8925e-01, time/batch = 2.8234s	
5/597600 (epoch 0.000), train_loss = 2.67117192, grad/param norm = 7.6747e-01, time/batch = 2.9711s	
6/597600 (epoch 0.001), train_loss = 2.62904019, grad/param norm = 7.3067e-01, time/batch = 2.9847s	
7/597600 (epoch 0.001), train_loss = 2.60829947, grad/param norm = 5.6794e-01, time/batch = 2.9377s	
8/597600 (epoch 0.001), train_loss = 2.60034659, grad/param norm = 5.0198e-01, time/batch = 3.1517s	
9/597600 (epoch 0.001), train_loss = 2.58412936, grad/param norm = 4.7694e-01, time/batch = 3.4833s	
...
859/597600 (epoch 0.072), train_loss = 1.81138613, grad/param norm = 9.2530e-02, time/batch = 6.4429s	
...


➜  rnn $ th sample.lua cv/lm_lstm_epoch3.68_1.8057.t7 -gpuid -1 -primetext "جناب آقای"
➜  rnn & th sample.lua cv/lm_lstm_epoch0.17_1.1777.t7 -gpuid -1 
creating an lstm...	
missing seed text, using uniform probability over first character	
--------------------------	
ª± در توسط برای مواد در سبوران بعد و اختطالی خود روانی در وقت_«جنی به نزر_بود. از دیکت» برای نانها، ترک‌ها و به طفل این مورد می‌دهد.

 ۲۰ برد.»
 تنحوب ۵-۸ د.
 شناسی برخچدر زیر ۱۱۸۹۷ به دانشمر منتشقه_کاده شد و معن خطود مسه داستنگ ازخان درآورد. برمنزک_ایجون تختید بازی اصلی (خود برکرند) خورزیده ۢ بدی از خران بلیبادار)
 هش رفت»"سنی و تقغیقی و (ه¬ مازنده،) در شمیفیاس
 سیاست_شیس هینواشته است.
 شخد_بسیاسننامه حزام و جایستانی است.
 معنه طورت جنک آباش برخاستوادی سازمانندستن در کشتنی و پیسونه برای عامین شکادی مذایی توفا فرود.
 زیب را اعتقاد‌گارنا قوم به_بودن‌" Ø و می‌باشد. هیچوین میگرودند.
 بعمی ختطراسی قهرام فاده"حیی و حوزنای بود، مسینج قسارند_که یکی و یکبیمولل (زکرستاره. و آلم می‌شود. قرمت کشبرگی پس اژورهام نامعند_دیگر شزدی در جنگ‌خوستان، این به‌کنگا، که براسب محئوسین قببتن نهح‌های شه_صفوع در هرچون حمارته، در سیاز_رمنیسی جانوام، خوزی مدارند، در ناو عنوان جلی یخوان، یکی از زیفواش است. اولین_زم روز بیالی که به بسیاری که قی علسی، درک دیگر حدون دخشت و پدیستانی صدب داد که سفاض به ارومن ی سنگ_جهین شاعس سیاسی، ایران سازدگردری به آنها به عحبقه سازها میâش را برای باند‌ها به همین بسته کرده‌از می‌شد. در می‌ترازه و تا Û
