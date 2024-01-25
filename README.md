# Converting Hamshahri City Dataset from XML to CSV

## Introduction

The Hamshahri Dataset, specifically the Pikre Hamshahri corpus, is a substantial Persian text collection based on the Iranian newspaper Hamshahri. Initially compiled and edited by Ehsan Daroudi from Tehran University, a subsequent group led by Abulfazl Al-Ahmadcontinued to build and enhance this corpus. It marked the creation of the first Persian text collection suitable for information retrieval evaluation purposes.
Source : wikipedia
## Issue

When you download the Hamshahri corpus, you will encounter a series of files in XML format. This documentation outlines the process of converting these XML files into CSV format for ease of use and analysis.

## Sample Data

Here is a sample data entry from the Hamshahri Dataset:

```xml
<DOC>
<DOCID>HAM2-830617-013</DOCID>
<DOCNO>HAM2-830617-013</DOCNO>
<ORIGINALFILE>/1383/830617/irshahr/_darsh.htm</ORIGINALFILE>
<ISSUE>سه شنبه 17 شهريور 1383 - سال دوازدهم - شماره - 3489</ISSUE>
<DATE calender="Western">2004-09-07</DATE>
<DATE calender="Persian">1383/06/17</DATE>
<CAT xml:lang="fa">گوناگون</CAT>
<CAT xml:lang="en">Miscellaneous</CAT>
<TITLE>
<![CDATA[تسهيلا ت
افتتاح يك مدرسه آلماني ديگر]]>
</TITLE>
<TEXT>
<IMAGE>/1383/830617/irshahr/015178.jpg</IMAGE>
<![CDATA[
در آستانه سال تحصيلي جديد، مدرسه ساخت آلماني ها در منطقه زلزله زده رزن افتتاح مي شود.
اين هفتمين مدرسه ساخته شده توسط دولت آلمان است كه روز يكشنبه در منطقه زلزله زده شهرستان رزن از توابع استان همدان به بهره برداري رسيد. فرماندار شهرستان رزن گفت: اين مدرسه در زميني به گستره 2 هزار متر مربع و زيربناي 548 متر مربع در شهر قروه درجزين احداث شده است.
محسن مرادي پناه افزود: براي احداث اين مدرسه 6 كلاسه 902 ميليون و 295 هزار ريال از محل كمك هاي دولت آلمان به مردم زلزله زده هزينه شده است.
دولت آلمان در پي حادثه دلخراش زلزله سال 81 هزينه ساخت 7 باب مدرسه در شهرستان رزن را به عهده گرفته است.
وي افزود: با ساخت و تجهيز 112 كلاس درس طي 2 سال گذشته توسط آلمان، 3 هزار و 331 نفر از دانش آموزان شهرستان رزن از امكانات آموزشي بهره مند شدند.
مدارس اهدايي دولت آلمان تاكنون در شهر و روستاهاي قروه درجزين، كهارد، بابانظر، چورمق، فارسجين، سوزن و قادرخلج از توابع شهرستان رزن طي 2 سال گذشته به بهره برداري رسيده است. در اين مدارس البته درس به زبان آلماني تدريس نمي شود!]]>
</TEXT>
</DOC>

```
## Conversion Process

To convert the XML files to CSV, follow these steps:

1. **Download the Hamshahri Corpus:**
   - Obtain the Hamshahri dataset, which typically comes in XML format.

2. **Identify XML Files:**
   - In the downloaded dataset, locate the XML files containing the textual data.

3. **Clone or Download this Repository:**
   - Clone or download the repository containing the conversion script and documentation.

4. **Run the Conversion Script:**
   - Execute the provided script to convert the XML files to CSV.
     ```bash
     python convert_xml_to_csv.py
     ```

5. **Review the Output:**
   - The script will generate three CSV files, namely 'val_data_encoded.csv,' 'train_data_encoded.csv,' and 'unique_encoded_labels.csv,' categorizing the data accordingly.
<img width="1105" alt="Screenshot 1402-11-05 at 9 45 41 at night" src="https://github.com/danialfarsi/hamshahri_corpus/assets/43178887/f1eeb614-aeb9-4a2a-8c5f-497d7f08b261">



## Repository Updates

This repository is actively maintained and updated. Feel free to check for the latest version of the conversion script or any additional documentation.

