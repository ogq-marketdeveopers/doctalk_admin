<template>
  <v-data-table
    :headers="headers"
    :items="desserts"
    :items-per-page="5"
    class="elevation-1"
  ></v-data-table>
</template>

<script>
export default {
  data() {
    return {
      headers: [
        {
          text: '구분',
          align: 'center',
          sortable: false,
          value: 'sortation'
        },
        { text: '일자', align: 'center', value: 'createdAt' },
        { text: '제목', align: 'center', value: 'title' },
        { text: '작성자', align: 'center', value: 'writer' },
        { text: '병원', align: 'center', value: 'hospital' },
        { text: '지식인', align: 'center', value: 'naver_kin_status' },
        {
          text: '미처리 신고수',
          align: 'center',
          value: 'number_unprocessed_reports'
        }
      ],
      desserts: [
        {
          sortation: '병원 상담글',
          createdAt: '2020-04-13 23:21:06',
          title:
            '인청 청라 32세/여 여드름, 여드름자국이 고민되어 치료를 알아보고 있습니다.',
          writer: '닥톡이',
          hospital: '닥톡병원 도곡점',
          naver_kin_status: '미등록',
          number_unprocessed_reports: '-'
        },
        {
          sortation: '병원 상담글',
          createdAt: '2020-04-13 23:21:06',
          title:
            '인청 청라 32세/여 여드름, 여드름자국이 고민되어 치료를 알아보고 있습니다.',
          writer: '닥톡이',
          hospital: '닥톡병원 도곡점',
          naver_kin_status: '미등록',
          number_unprocessed_reports: '-'
        },
        {
          sortation: '-',
          createdAt: '2020-04-13 23:21:06',
          title:
            '인청 청라 32세/여 여드름, 여드름자국이 고민되어 치료를 알아보고 있습니다.',
          writer: '닥톡이',
          hospital: '닥톡병원 도곡점',
          naver_kin_status: '미등록',
          number_unprocessed_reports: '-'
        },
        {
          sortation: '-',
          createdAt: '2020-04-13 23:21:06',
          title:
            '인청 청라 32세/여 여드름, 여드름자국이 고민되어 치료를 알아보고 있습니다.',
          writer: '닥톡이',
          hospital: '닥톡병원 도곡점',
          naver_kin_status: '미등록',
          number_unprocessed_reports: '-'
        },
        {
          sortation: '-',
          createdAt: '2020-04-13 23:21:06',
          title:
            '인청 청라 32세/여 여드름, 여드름자국이 고민되어 치료를 알아보고 있습니다.',
          writer: '닥톡이',
          hospital: '닥톡병원 도곡점',
          naver_kin_status: '미등록',
          number_unprocessed_reports: '-'
        },
        {
          sortation: '병원 상담글',
          createdAt: '2020-04-13 23:21:06',
          title:
            '인청 청라 32세/여 여드름, 여드름자국이 고민되어 치료를 알아보고 있습니다.',
          writer: '닥톡이',
          hospital: '닥톡병원 도곡점',
          naver_kin_status: '미등록',
          number_unprocessed_reports: '-'
        },
        {
          sortation: '병원 상담글',
          createdAt: '2020-04-13 23:21:06',
          title:
            '인청 청라 32세/여 여드름, 여드름자국이 고민되어 치료를 알아보고 있습니다.',
          writer: '닥톡이',
          hospital: '닥톡병원 도곡점',
          naver_kin_status: '미등록',
          number_unprocessed_reports: '-'
        },
        {
          sortation: '-',
          createdAt: '2020-04-13 23:21:06',
          title:
            '인청 청라 32세/여 여드름, 여드름자국이 고민되어 치료를 알아보고 있습니다.',
          writer: '닥톡이',
          hospital: '닥톡병원 도곡점',
          naver_kin_status: '미등록',
          number_unprocessed_reports: '-'
        },
        {
          sortation: '병원 상담글',
          createdAt: '2020-04-13 23:21:06',
          title:
            '인청 청라 32세/여 여드름, 여드름자국이 고민되어 치료를 알아보고 있습니다.',
          writer: '닥톡이',
          hospital: '닥톡병원 도곡점',
          naver_kin_status: '미등록',
          number_unprocessed_reports: '-'
        },
        {
          sortation: '병원 상담글',
          createdAt: '2020-04-13 23:21:06',
          title:
            '인청 청라 32세/여 여드름, 여드름자국이 고민되어 치료를 알아보고 있습니다.',
          writer: '닥톡이',
          hospital: '닥톡병원 도곡점',
          naver_kin_status: '미등록',
          number_unprocessed_reports: '-'
        }
      ]
    }
  }
}
</script>
