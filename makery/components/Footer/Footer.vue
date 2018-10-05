<template>
    <div class="container">
        <div class="col-12">
            <hr>
            <div class="row margin-auto">
                <div class="col-lg-8 col-md-10 col-sm-12 text-center" style="margin-left:auto">  
                    <p class="col-12">
                        <small>샌드위치팀 대표 장형준 사업자등록번호 149-21-00687 통신판매신고 제 2018-서울광진-0119 호</small>
                        <br />
                        <small>서울시 광진구 아차산로41길 5-4 고객센터 0507-0079-9788 FAX 050-4130-0120</small>
                    </p>

                    <ul>
                        <li>                
                            <nuxt-link to="/contact/individual">
                                개인정보 처리 방침
                            </nuxt-link>
                        </li>
                        <li>
                            <nuxt-link to="/contact/use">
                                이용 약관
                            </nuxt-link>
                        </li>
                    </ul>
                </div>
                <!-- 기업은행 안심 이체 마크 -->
                <div class="credits col-lg-2 col-md-2 col-sm-12">
                    <div class="text-center">
                        <script _ajs_='46_-3846aef71b04ab30' _ah_='-1777199459'>
                            function onPopAuthMark(key) {
                                window.open('', 'AUTHMARK_POPUP', 'height=900, width=630, status=yes, toolbar=no, menubar=no, location=no');
                                document.AUTHMARK_FORM.authmarkinfo.value = key;
                                document.AUTHMARK_FORM.action = 'https://kiup.ibk.co.kr/uib/jsp/guest/esc/esc1030/esc103020/CESC302020_i.jsp';
                                document.AUTHMARK_FORM.target = 'AUTHMARK_POPUP';
                                document.AUTHMARK_FORM.submit();
                            }
                        </script>
                        <FORM name='AUTHMARK_FORM' METHOD='POST'>
                            <input type="hidden" name="authmarkinfo">
                        </FORM>
                        <a href="javascript:onPopAuthMark('ee78a55e8239b9bc47b91fe4b5d2ec47')">
                            <img src='https://kiup.ibk.co.kr/IBK/uib/ecb/img/KO/esc/sub/imgIbkMark.gif' alt='인증마크' border='0' />
                        </a>
                        <!--기업은행안심이체 인증마크 적용 종료 -->
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    div{
        background-color: cover
    }
    
    p {
        text-align: center
    }

    li{
        display: inline-block;
        margin: 10px;
    }
    ul{
        padding: 0;
    }
</style>
