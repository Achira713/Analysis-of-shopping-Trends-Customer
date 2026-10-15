# Analysis-of-shopping-Trends-Customer
# คำอธิบายข้อมูล (Data Description)

โฟลเดอร์นี้อธิบายข้อมูลที่ใช้ในโครงงาน **IT Salary Analysis**

## 1. แหล่งที่มาและสิทธิ์การใช้ข้อมูล

| หัวข้อ | รายละเอียด |
| --- | --- |
| ชื่อชุดข้อมูล | Shopping Trends And Customer Behaviour Dataset |
| แหล่งที่มาเดิม | https://www.kaggle.com/datasets/sahilislam007/shopping-trends-and-customer-behaviour-dataset |
| ประเภทข้อมูล | ข้อมูลประวัติการสั่งซื้อและพฤติกรรมลูกค้า (Transactional Data) 1 แถวต่อการสั่งซื้อ 1 รายการ |

## 2. ไฟล์ในโฟลเดอร์นี้

| ตำแหน่งไฟล์ | คำอธิบาย |
| --- | --- |
| `data/raw/Shopping Trends And Customer Behaviour Dataset.csv` | ไฟล์ตามที่ดาวน์โหลดมาไม่มีข้อมูลศูนย์หาย มี 3,900 แถว 18 คอลัมน์ (รวมคอลัมน์ Timestamp ในไฟล์ที่ตรวจ) |




## 3. พจนานุกรมข้อมูล (Data Dictionary) ของ `Shopping Trends And Customer Behaviour Dataset.csv`

ข้อมูลไม่มีข้อมูลศูนย์หายมีทั้งหมด 3,900 แถว ตารางต่อไปนี้แสดงชื่อคอลัมน์ ชนิดข้อมูล คำอธิบาย และจำนวนค่าว่างของแต่ละคอลัมน์

| คอลัมน์ | ชื่อคอลัมน์เดิม | ชนิดข้อมูล | คำอธิบาย / ค่าที่เป็นไปได้ | ค่าว่าง |
| --- | --- | --- | --- | ---: |
| `unnamed_0` | Unnamed: 0 | ตัวเลข |ลำดับแถวรายการข้อมูล (Index)| 0 |
| `customer_id` | Customer ID | ตัวเลข | รหัสประจำตัวของลูกค้า (มีทั้งหมด 3,900 คน) | 0 |
| `age` | Age | ตัวเลข | อายุของลูกค้า หน่วยเป็นปี | 0 |
| `gender` | Gender | ข้อความ | เพศของลูกค้า ได้แก่ Male และ Female | 0 |
| `item_purchased` | Item Purchased | ข้อความ | ชื่อสินค้าที่ลูกค้าซื้อ มีทั้งหมด 25 รายการ (เช่น Blouse, Sweater, Jeans)| 0 |
| `category` | Category | ข้อความ | หมวดหมู่สินค้า ได้แก่ Clothing, Footwear, Outerwear และ Accessories | 0 |
| `purchase_amount_usd` | Purchase Amount (USD)| ตัวเลข | ยอดเงินในการซื้อสินค้า หน่วยเป็นดอลลาร์สหรัฐ (USD) | 0 |
| `location` | Location | ข้อความ | รัฐหรือสถานที่สั่งซื้อ มีทั้งหมด 50 รัฐ (เช่น Kentucky, Maine) | 0|
| `color` | Color | ข้อความ | สีของสินค้าที่ซื้อ มีทั้งหมด 25 สี (เช่น Gray, Maroon, White) | 0 |
| `season` | Season | ข้อความ |ฤดูกาลที่สั่งซื้อ ได้แก่ Winter, Spring, Summer และ Fall| 0 |
| `review_rating` | Review Rating | ตัวเลข | คะแนนรีวิวสินค้าจากลูกค้า (ช่วง 2.5 ถึง 5.0)| 0 |
| `subscription_status` | Subscription Status | ข้อความ | สถานะการสมัครสมาชิกบริการ ได้แก่ Yes และ No | 0 |
| `shipping_type` | Shipping Type | ข้อความ | ประเภทการจัดส่งสินค้า ได้แก่ Express, Free Shipping, Next Day Air, Standard, 2-Day Shipping และ Store Pickup | 0 |
| `discount_applied` | Discount Applied | ข้อความ | มีการใช้ส่วนลดหรือไม่ ได้แก่ Yes และ No | 0 |
| `promo_code_used` | Promo Code Used | ข้อความ |มีการใช้โค้ดส่วนลดหรือไม่ ได้แก่ Yes และ No| 0 |
| `previous_purchases` | Previous Purchases | ตัวเลข | จำนวนครั้งที่ลูกค้าเคยสั่งซื้อสินค้ามาก่อนหน้า | 0 |
| `payment_method` | Payment Method | ข้อความ | ช่องทางการชำระเงิน ได้แก่ Venmo, Cash, Credit Card, PayPal, Bank Transfer และ Debit Card | 0 |
| `frequency_of_purchases` | Frequency of Purchases | ข้อความ | ความถี่ในการสั่งซื้อสินค้า ได้แก่ Fortnightly, Weekly, Annually, Quarterly, Bi-Weekly, Monthly และ Every 3 Months| 0 |

**หมายเหตุ**
- จจำนวนค่าว่าง (Missing Values) นับจากข้อมูลหลังทำความสะอาดแล้ว จำนวน 3,900 แถว พบว่าไม่มีค่าว่างอยู่ในชุดข้อมูลเลย (Missing Values = 0)



หน่วยของจำนวนเงินทั้งหมดในคอลัมน์ Purchase Amount (USD) คือ ดอลลาร์สหรัฐ (USD)
