# 🚢 Titanic Survival Analysis Project

## 📋 Mục lục
- [Tổng quan dự án](#tổng-quan-dự-án)
- [Nguồn dữ liệu](#nguồn-dữ-liệu)
- [Cấu trúc dữ liệu](#cấu-trúc-dữ-liệu)
- [Yêu cầu phân tích](#yêu-cầu-phân-tích)

## 🌟 Tổng quan dự án

Dự án **Titanic Survival Analysis** là một dự án phân tích và trực quan hóa dữ liệu kinh điển, sử dụng bộ dữ liệu nổi tiếng từ thảm họa tàu Titanic năm 1912. Dự án nhằm mục đích:

- **Phân tích** các yếu tố ảnh hưởng đến tỷ lệ sống sót của hành khách
- **Trực quan hóa** dữ liệu để hiểu rõ hơn về đặc điểm của hành khách và mối quan hệ giữa các yếu tố

Đây là một trong những bài toán kinh điển trong lĩnh vực khoa học dữ liệu và phân tích dữ liệu khám phá.

## 📊 Nguồn dữ liệu

Dữ liệu được lấy từ cuộc thi **[Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/overview)** trên Kaggle.

### Thông tin cuộc thi:
- **Nguồn**: Kaggle Competition
- **Số lượng hành khách**: 1.309 người (train + test)
- **Thời gian**: Thảm họa xảy ra ngày 15/04/1912

### Tập dữ liệu:
- `titanic_data.csv`: 891 hành khách kèm nhãn sống sót (sử dụng để phân tích và trực quan hóa)

## 🔍 Cấu trúc dữ liệu

### Các thuộc tính chính:

| Thuộc tính | Mô tả | Kiểu dữ liệu |
|-----------|--------|-------------|
| **PassengerId** | ID duy nhất của hành khách | Integer |
| **Survived** | Trạng thái sống sót (0 = Không, 1 = Có) | Integer |
| **Pclass** | Hạng vé (1 = hạng nhất, 2 = hạng nhì, 3 = hạng ba) | Integer |
| **Name** | Tên hành khách | String |
| **Sex** | Giới tính | String (male/female) |
| **Age** | Tuổi | Float |
| **SibSp** | Số anh chị em/vợ chồng đi cùng | Integer |
| **Parch** | Số cha mẹ/con cái đi cùng | Integer |
| **Ticket** | Số vé | String |
| **Fare** | Giá vé | Float |
| **Cabin** | Số cabin | String |
| **Embarked** | Cảng lên tàu (C = Cherbourg, Q = Queenstown, S = Southampton) | String |

## 📈 Yêu cầu phân tích

### Các câu hỏi cần trả lời:

1. **Nhân khẩu học**: Đặc điểm hành khách theo tuổi, giới tính, hạng vé?
2. **Tỷ lệ sống sót**: Ai có khả năng sống sót cao hơn?
3. **Mối quan hệ**: Giữa các yếu tố như tuổi, giới tính, hạng vé với khả năng sống sót?
4. **Phân tích sâu**: Các yếu tố nào ảnh hưởng nhiều nhất đến khả năng sống sót?

### Các phân tích cần thực hiện:

- ✅ Phân tích thống kê cơ bản
- ✅ Kiểm tra dữ liệu thiếu
- ✅ Xử lý dữ liệu thiếu và ngoại lai
- ✅ Phân tích tương quan
- ✅ Kiểm định giả thuyết
- ✅ Trực quan hóa dữ liệu
