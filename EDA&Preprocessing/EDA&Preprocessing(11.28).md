# 24.11.28(EDA&Preprocessing)

- 60191682 임준용
1. **데이터셋 맨 위 5개 관측치**

![image](https://github.com/user-attachments/assets/f8f76d1d-9bef-4e6b-801b-97a65056e2ad)

1. **데이터셋 맨 아래 5개 관측치**

![image 1](https://github.com/user-attachments/assets/e8d915bd-b084-46bd-af4c-4321f71a7e7f)

1. **데이터셋 전체 정보**

![image 2](https://github.com/user-attachments/assets/8fefa193-af3d-4a32-9bdc-d8db29e8dc8c)

1. **데이터셋 컬럼 정보(총 32개)**
   - hotel: 호텔의 종류(Resort Hotel / City Hotel)
   - is_canceled: 호텔 예약 취소 여부(1: 취소함 / 2: 취소 안함)
   - lead_time: 호텔 예약 날짜와 호텔 도착 날짜 사이 경과 일수
   - arrival_date_year: 호텔에 도착한 년도
   - arrival_date_month: 호텔에 도착한 월
   - arrival_date_week_number: 호텔에 도착한 주
   - arrival_date_day_of_month: 호텔에 도착한 일
   - stays_in_weekend_nights: 주말에 숙박한 일 수
   - stays_in_week_nights: 주중에 숙박한 일 수
   - adults: 호텔에 방문한 어른 수
   - children: 호텔에 방문한 청소년 수
   - babies: 호텔에 방문한 유아 수
   - meal: 예약된 식사 유형(Undefined / SC는 식사가 없는 경우)
   - country: 호텔을 예약한 손님의 국가
   - market_segment: 마켓 구분(TA: Travel Agents / TO: Tour Operator)
   (아래 컬럼이랑 비슷한 느낌인거 같은데, 더 찾아보겠습니다)
   - distrubution_channel: 예약 채널(TA: Travel Agents / TO: Tour Operator)
   (생산자에서 소비자에게 이르기까지의 방식, 채널)
   - is_repeated_guest: 호텔 재방문 손님 여부(1: 맞음 / 2: 아님)
   - previous_cancellations: 해당 손님의 과거 예약 취소 횟수
   - prevoius_bookings_not_canceled: 해당 손님의 과거 예약 취소를 하지 않은 횟수
   - reserved_room_type: 예약된 객실 유형(익명성을 위해 명칭 대신 코드로 표시)
   - assigned_room_type: 예약에 배정된 객실 유형
   - booking_changes: 예약 후 예약 변경 혹은 수정 횟수
   - deposit_type: 보증금 지불 여부
   - agent: 호텔 예약 여행 에이전시 ID
   - company: 호텔 예약 담당 회사 ID
   - days_in_waiting_list: 예약이 완료될 때까지 대기 목록에 속한 기간
   - customer_type: 고객 유형
   - adr: 평균 일일 숙박비용
   - required_car_parking_spaces: 고객이 요구한 주차공간 수
   - total_of_special_requests: 고객이 요청한 특별 요청 수(예: 트윈 침대, 높은 층수)
   - reservation_status: 마지막 예약 상태
   - reservation_status_date: 마지막 예약 상태가 설정된 날짜
