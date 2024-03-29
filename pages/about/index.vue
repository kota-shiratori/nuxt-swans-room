<template>
    <main>
        <div class="l-content">
            <div class="section">
                <div class="section__ttl"><span class="section__ttl--inner">About</span></div>
                <div class="my-history">
                    <div class="my-history__item">
                        <div class="my-history__number">
                            <span class="__shape"></span>
                            <span class="__label">1997年</span>
                        </div>
                        <h3 class="my-history__ttl">沖縄に生まれ名古屋に育つ</h3>
                        <div class="my-history__body">
                            <p class="my-history__txt">沖縄県出身の母と北海道出身の父との間に生まれ、名古屋で育つ。</p>
                        </div>
                    </div>
                    <div class="my-history__item">
                        <div class="my-history__number">
                            <span class="__shape"></span>
                            <span class="__label">2010年4月〜</span>
                        </div>
                        <h3 class="my-history__ttl">中学時代</h3>
                        <div class="my-history__body">
                            <p class="my-history__txt">野球部に入部。ひたすら部活動に励み、副キャプテンとして活動。</p>
                        </div>
                    </div>
                    <div class="my-history__item">
                        <div class="my-history__number">
                            <span class="__shape"></span>
                            <span class="__label">2013年4月〜</span>
                        </div>
                        <h3 class="my-history__ttl">高校時代</h3>
                        <div class="my-history__body">
                            <p class="my-history__txt">中学時代とは一転し、サッカー部に入部。ここでも副キャプテンとして活動。</p>
                        </div>
                    </div>
                    <div class="my-history__item">
                        <div class="my-history__number">
                            <span class="__shape"></span>
                            <span class="__label">2016年4月〜</span>
                        </div>
                        <h3 class="my-history__ttl">看護助手時代</h3>
                        <div class="my-history__body">
                            <p class="my-history__txt">進路に悩み、両親ともに医療関係者だったこともあり、一度看護助手として就職。</p>
                        </div>
                    </div>
                    <div class="my-history__item">
                        <div class="my-history__number">
                            <span class="__shape"></span>
                            <span class="__label">2017年4月〜</span>
                        </div>
                        <h3 class="my-history__ttl">専門時代</h3>
                        <div class="my-history__body">
                            <p class="my-history__txt">看護助手を経て、看護師として国家資格を取るために専門学校へ入学。看護師国家資格取得。</p>
                        </div>
                    </div>
                    <div class="my-history__item">
                        <div class="my-history__number">
                            <span class="__shape"></span>
                            <span class="__label">2020年4月〜</span>
                        </div>
                        <h3 class="my-history__ttl">看護師時代</h3>
                        <div class="my-history__body">
                            <p class="my-history__txt">集中治療室に配属。急性期医療メンバーの一員として奮闘。</p>
                        </div>
                    </div>
                    <div class="my-history__item">
                        <div class="my-history__number">
                            <span class="__shape"></span>
                            <span class="__label">2022年4月〜</span>
                        </div>
                        <h3 class="my-history__ttl">フリーランスとして独立</h3>
                        <div class="my-history__body">
                            <p class="my-history__txt">
                                もっとクリエイティブな働き方がしたいと思い、看護師として働きながらWebのことを独学で学び、会社員を辞め、フリーランスとして活動中。
                            </p>
                        </div>
                    </div>
                    <div class="my-history__item">
                        <div class="my-history__number">
                            <span class="__shape"></span>
                            <span class="__label">2023年10月〜</span>
                        </div>
                        <h3 class="my-history__ttl">筋トレにハマる</h3>
                        <div class="my-history__body">
                            <p class="my-history__txt">
                                筋トレにハマり、ベンチプレス100kg達成。4ヶ月で10kgの増量。
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<style>
/*----------------------------------------
	About
----------------------------------------*/
.my-history__item {
    position: relative;
    padding: 0 0 2em 24px;
}

.my-history__item:last-child::before {
    border-left: none;
}

.my-history__item::before {
    border-left: 1px dashed rgba(200, 200, 200, 0.5);
    content: "";
    display: block;
    height: 100%;
    left: 23px;
    position: absolute;
    top: 0;
    width: 0;
}

.my-history__item::before {
    border-left: 2px solid rgba(200, 200, 200, 0.5);
    height: calc(100% - 20px);
    left: 7px;
    top: 18px;
}

.my-history__number {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    margin-left: -24px;
}

.my-history__number .__shape {
    width: 16px;
    height: 16px;
    border-radius: 50%;
    background: #333;
    margin-right: 8px;
}

.my-history__number .__label {
    font-size: 0.875rem;
}

.my-history__ttl {
    margin-top: 10px;
    font-size: 1.125rem;
}

.my-history__body {
    margin-top: 15px;
}

.my-history__txt {
    line-height: 1.7;
    font-weight: 400;
    font-size: 0.9375rem;
}

@media screen and (min-width: 992px) {
    .my-history {
        padding: 0 30px;
    }
}
</style>