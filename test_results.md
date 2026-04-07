# Test 1 - Direct Answer

Bạn: Xin chào, tôi đang muốn đi du lịch nhưng chưa biết đi đâu

TravelBuddy đang suy nghĩ...
  [Log] Trả lời trực tiếp

TravelBuddy: Chào bạn! Rất vui được giúp đỡ bạn lên kế hoạch cho chuyến đi. Bạn có thể cho mình biết một số thông tin như thời gian bạn dự định đi, ngân sách bạn có và bạn thích khám phá địa điểm nào (biển, núi, thành phố, văn hóa, ẩm thực, v.v.) không?

# Test 2 - Single Tool-call

Bạn: Tìm giúp tôi chuyến bay từ Hà Nội đi Đà Nẵng

TravelBuddy đang suy nghĩ...
  [Log] Trả lời trực tiếp

TravelBuddy: Bạn dự định đi Đà Nẵng vào ngày nào? Và có ai đi cùng bạn không? Điều này sẽ giúp tôi tìm kiếm chuyến bay chính xác hơn.

# Test 3 - Multi-Step Tool Chaining

Bạn: Tôi ở Hà Nội, muốn đi Phú Quốc 2 đêm, budget 5 triệu. Tư vấn giúp!

TravelBuddy đang suy nghĩ...
  [Log] Gọi tool: search_flights({'origin': 'Hà Nội', 'destination': 'Phú Quốc'})
  [Log] Gọi tool: calculate_budget({'total_budget': 5000000, 'expenses': 'vé máy bay: 1350000'})
  [Log] Gọi tool: search_hotels({'city': 'Phú Quốc', 'max_price_per_night': 1825000})
  [Log] Trả lời trực tiếp

TravelBuddy: Dưới đây là thông tin chuyến đi của bạn từ Hà Nội đến Phú Quốc:

**Chuyến bay:**
- **Hãng:** VietJet Air (economy)
- **Giờ bay:** 10:00 -> 12:15
- **Giá:** 1.350.000₫

**Khách sạn:**
1. **9Station Hostel** (2 sao)
   - Khu vực: Dương Đông
   - Rating: 4.5/5
   - Giá: 200.000₫/đêm
   - **Tổng cho 2 đêm:** 400.000₫

2. **Sol by Meliá** (4 sao)
   - Khu vực: Bãi Trường
   - Rating: 4.2/5
   - Giá: 1.500.000₫/đêm
   - **Tổng cho 2 đêm:** 3.000.000₫

3. **Lahana Resort** (3 sao)
   - Khu vực: Dương Đông
   - Rating: 4.0/5
   - Giá: 800.000₫/đêm
   - **Tổng cho 2 đêm:** 1.600.000₫

**Tổng chi phí ước tính:**
- Vé máy bay: 1.350.000₫
- Khách sạn (ví dụ chọn 9Station Hostel): 400.000₫
- **Tổng chi phí:** 1.750.000₫

**Ngân sách còn lại sau khi thanh toán:** 5.000.000₫ - 1.750.000₫ = 3.250.000₫

**Gợi ý thêm:**
- Bạn có thể chọn giữa các khách sạn tùy theo sở thích và ngân sách. Nếu muốn trải nghiệm chất lượng cao hơn, hãy cân nhắc "Sol by Meliá".
- Nếu bạn cần thêm thông tin hoặc giúp đỡ về việc đặt vé và phòng, cứ cho mình biết nhé!

# Test 4 - Missing Info / Clarification

Bạn: Tôi muốn đặt khách sạn

TravelBuddy đang suy nghĩ...
  [Log] Trả lời trực tiếp

TravelBuddy: Tuyệt vời! Bạn có thể cho mình biết bạn muốn đặt khách sạn ở đâu, ngân sách mỗi đêm là bao nhiêu, và thời gian bạn dự định lưu trú không?

# Test 5 - Guardrail / Refusal

Bạn: Giải giúp tôi bài tập lập trình Python về linked list

TravelBuddy đang suy nghĩ...
  [Log] Trả lời trực tiếp

TravelBuddy: Xin lỗi, nhưng mình không thể giúp bạn với yêu cầu đó. Tuy nhiên, nếu bạn có bất kỳ câu hỏi hay cần trợ giúp về du lịch, hãy cho mình biết nhé!