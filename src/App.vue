<template>
  <div id="app">
    <header class="pb-5 pt-5 text-light bg-success">
        <h1 class="container">Клуб 111</h1>
        <h2 class="container">Вплавь, на велосипеде и бегом</h2>
    </header>

    <button id="go-top" class="btn btn-info" @click='onTop'>Наверх</button>

    <nav class="navbar sticky-top navbar-expand-lg navbar-light bg-even">
        <div class="container">
            <a class="navbar-brand" href="#">Клуб 111</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#mainMenu" aria-controls="mainMenu" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
            <div class="collapse navbar-collapse" id="mainMenu">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item"><a class="nav-link" href="#news">Новости</a></li>
                    <li class="nav-item"><a class="nav-link" href="#mission">Миссия</a></li>
                    <li class="nav-item"><a class="nav-link" href="#members">Участники клуба</a></li>
                    <li class="nav-item"><a class="nav-link" href="#results">Результаты соревнований</a></li>
                    <li class="nav-item"><a class="nav-link" href="#photo">Фотогалерея</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <main>
        <section id="video" class="pb-5 pt-5">
            <div class="container">
                <h2>Приветсвуем Вас</h2>
                <p>Две минуты о том, что здесь происходит: </p>
                <p class="embed-responsive embed-responsive-16by9">
                    <iframe class="embed-responsive-item" src="//vk.com/video_ext.php?oid=-48128871&id=456239106&hash=4790b2baf60867da&hd=2" widtd="769" height="480" frameborder="0" allowfullscreen></iframe>
                </p>
            </div>
        </section>
        <section id="news" class="bg-even pb-5 pt-5">
            <div class="container">
                <h2>Новости</h2>
                <p>
                    Летний сезон 2019 окончен. Скоро мы напишем о результатах...
                </p>
            </div>
        </section>
        <section id="mission" class="pb-5 pt-5">
            <div class="container">
                <h2>Миссия</h2>
                <h3 class="h4 text-center">
                    Вместо предисловия
                </h3>
                <p>
                    Мы рады приветствовать вас на сайте «Клуба 111»! Изначально мы планировали рассказать здесь о целях клуба, пользе спорта и поиске мотивации. Однако все попытки призвать к физическому развитию неизменно сводились к банальному лозунгу «Занимайтесь спортом
                    — будете здоровы (веселы/бодры/счастливы)». Поэтому мы решили просто рассказать о том, что двигает вперед нас.
                </p>
                <h3 class="h4 text-center">
                    Дорогие друзья!
                </h3>
                <p>
                    Мы все о чем-то мечтаем. В детстве — быть сильными, смелыми, выносливыми, красивыми (и не говорите, что не было такого). С годами мечты остаются все те же, только к ним прибавляется прозаичное желание найти время для собственного развития. Ссылаясь на
                    чужие умные мысли, мы начинаем оправдывать свое бездействие отсутствием мотивации. Но если вдуматься, мотивация никуда не пропала, она с детства по-прежнему с нами. Мы все еще хотим быть самыми-самыми. Не хватает только стимула — сделать
                    шаг вперед, научиться управлять временем.
                </p>
                <p>
                    Наш клуб может стать таким стимулом. Здесь вы окажетесь в окружении единомышленников, которые не дают будничной рутине победить мечту. Здесь не надо бояться выглядеть нелепо на тренировке или прийти последним на соревнованиях. Каждый участник нашего клуба,
                    без риска для здоровья и собственного достоинства, бросает вызов себе, чтобы испытать, что значит быть самым-самым.
                </p>
                <p>
                    Никто не упрекнет вас в спортивной неудаче или скромных показателях. Наша главная победа — над собой. Мы призываем вас попробовать свои силы и обещаем, что все получится и когда-нибудь вы с гордостью скажете себе: «Я сделал это!».
                </p>
                <p>
                    Самыми-самыми мы хотим стать и для собственных детей, чтобы воспитать их на своем примере, научить их смело постигать неизведанное, преодолевать трудности, покорять новые вершины, чтобы когда-нибудь они стали самыми-самыми уже для своих детей. Спорт —
                    это часть культуры, которая, как известно, не передается по наследству — ее можно только воспитать.
                </p>
                <p>
                    Закончу свое обращение словами из замечательной книги Джона Кэллоса <a href="https://drive.google.com/file/d/0B-4SKPIGbDX3OG5GQjg2UUxYajA/view" target="_blank">«Железный человек есть в каждом»:</a>
                </p>
                <p>
                    <i>
              «Большинство таких пребывает в состоянии постоянного стресса. Они нарушают данные себе обещания и тяготятся чувством вины и стыда, обделяя вниманием друзей и близких и небрежно относятся к собственному здоровью. Все, кроме работы, откладывается на потом, на завтра — слишком сильна иллюзия, что «когда-нибудь я сумею остановится., заняться собой, наладить отношения в семье и начать тренировать малую бейсбольную лигу».
              Мне как никому другому хорошо известны эти отговорки: когда-то я не раз успокаивал себя именно таким образом.
              Среди моих знакомых очень много таких людей по всей стране, и я прекрасно понимаю их страхи, надежды, чувство вины и сожаления. Знаю, что они и дальше, придерживаясь избранного курса, будут следовать по пути несдержанных обещаний и несбывшихся надежд – до тех пор, пока мир вокруг не начнут рушиться. Только это сможет заставить их пересмотреть приоритеты и начать действовать, но пока в их жизни не случится некий серьезный перелом – смена работы, развод или резкое ухудшение здоровья, они так и будут приносить себя в жертву и копить стресс, мучаясь угрызениями совести и теряя уважение к себе».
            </i>
                </p>
                <p>
                    Полную версию книги читайте <a href="https://drive.google.com/open?id=0B-4SKPIGbDX3OG5GQjg2UUxYajA">здесь</a>.
                </p>
                <p>
                    Если вы хотите тренироваться регулярно, чтобы поддерживать форму или готовиться к клубным и региональным соревнованиям, напишите нам, нажав на ссылку: «стать участником клуба», или на электронную почту <a href="mailto:chernukhin@dtvs.ru">chernukhin@dtvs.ru</a>.
                </p>
                <p>
                    В соответствующих разделах сайта вы сможете ознакомиться с предстоящими мероприятиями (тренировками и соревнованиями), а так же заранее зарегистрироваться для участия в них. Надеюсь, что <a href="#photo">фотогалерея</a> и <a href="#video">видеозарисовка</a> из жизни участников клуба поможет вам
                    сделать правильный выбор.
                </p>
                <p class="text-right">
                    Фомичев Д.В.
                </p>
            </div>
        </section>

        <section id="members" class="bg-even pb-5 pt-5">
            <div class="container">
                <h2>Участники клуба</h2>
                <p>
                    Для поддержания физической формы и активного образа жизни инициативные сотрудники коттеджного посёлка создали «клуб 111» - клуб триатлона.
                </p>
                <p class="text-center">
                    <img class="img-fluid rounded" src="./img/club111.jpg" alt="club111" />
                </p>
                <p>
                    Члены клуба являются сотрудниками Технополис GS и регулярно принимают участие в международных соревнованиях по триатлону. Каждый год в августе на территории посёлка проходит открытый ежегодный чемпионат по триатлону.
                </p>
            </div>
        </section>

        <section id="results" class="pb-5 pt-5">
            <div class="container">
                <h2>Результаты соревнований</h2>
                <p>Тут будет размещены результаты соревнований</p>
            </div>
        </section>

        <section id="photo" class="bg-even pb-5 pt-5">
            <div class="container">
                <h2>Фотогалерея</h2>
                <div class="row text-center">
                    <div class="col-lg-3 col-md-4 col-6 pb-3 text-box">
                        <a target="_blank" href="https://drive.google.com/drive/folders/0B-4SKPIGbDX3SmI1Zk1IWUd3ejQ">
                            <p class="text-size-wrap">Соревнования 14.08.2016 Триатлон спринт GS</p>
                            <img class="img-fluid rounded" src="./img/image121.jpg">
                        </a>
                    </div>
                    <div class="col-lg-3 col-md-4 col-6 text-box">
                        <a target="_blank" href="https://drive.google.com/drive/folders/0B-4SKPIGbDX3OTlEbGRuSVlBR1E">
                            <p class="text-size-wrap">Соревнования 19.12.2016 Плаванье в зале</p>
                            <img class="img-fluid rounded" src="./img/image33.jpg">
                        </a>
                    </div>
                    <div class="col-lg-3 col-md-4 col-6 text-box">
                        <a target="_blank" href="https://drive.google.com/drive/folders/0B-4SKPIGbDX3TnBjX0twNURzVUE">
                            <p class="text-size-wrap">Соревнования 12.11.2016 Триатлон в зале</p>
                            <img class="img-fluid rounded" src="./img/image00.jpg">
                        </a>
                    </div>
                    <div class="col-lg-3 col-md-4 col-6 text-box">
                        <a target="_blank" href="https://drive.google.com/drive/folders/0B-4SKPIGbDX3SVRHNnpxVXNMMmc">
                            <p class="text-size-wrap">Встреча 25.12.2016 Подведение итогов за 2016 год</p>
                            <img class="img-fluid rounded" src="./img/itogi.jpg">
                        </a>
                    </div>
                    <div class="col-lg-3 col-md-4 col-6 text-box">
                        <a target="_blank" href="https://drive.google.com/drive/folders/0B-4SKPIGbDX3LWw4M21JMXdlUzg">
                            <p class="text-size-wrap">Соревнование 22.01.2017 Гумбиненский пробег</p>
                            <img class="img-fluid rounded" src="./img/probeg.jpg">
                        </a>
                    </div>
                    <div class="col-lg-3 col-md-4 col-6 text-box">
                        <a target="_blank" href="https://drive.google.com/drive/folders/0B-4SKPIGbDX3WWRMYVU0dTBuMzg">
                            <p class="text-size-wrap">25.04.2017 Годовщина клуба 111</p>
                            <img class="img-fluid rounded" src="./img/godovshina_cut.jpg">
                        </a>
                    </div>
                    <div class="col-lg-3 col-md-4 col-6 text-box">
                        <a target="_blank" href="https://drive.google.com/drive/folders/0B-4SKPIGbDX3MnpCQUFrdFdYWkE">
                            <p class="text-size-wrap">Tri Mondi 24.06.2017 Триатлон в Mondi</p>
                            <img class="img-fluid rounded" src="./img/trimondi.jpg">
                        </a>
                    </div>
                    <div class="col-lg-3 col-md-4 col-6 text-box">
                        <a target="_blank" href="https://drive.google.com/drive/folders/0B-4SKPIGbDX3LWhnZEo3azF0TEU">
                            <p class="text-size-wrap">Goldap 22.07.2017 Триатлон в Goldap</p>
                            <img class="img-fluid rounded" src="./img/goldap.jpg">
                        </a>
                    </div>
                    <div class="col-lg-3 col-md-4 col-6 text-box">
                        <a target="_blank" href="https://drive.google.com/drive/folders/0B-4SKPIGbDX3RmF6cFhOLW4tNVE">
                            <p class="text-size-wrap">Gdynia 19.08.2017 Триатлон в Gdynia</p>
                            <img class="img-fluid rounded" src="./img/gdynia.jpg">
                        </a>
                    </div>
                    <div class="col-lg-3 col-md-4 col-6 text-box">
                        <a target="_blank" href="https://drive.google.com/drive/folders/0B-4SKPIGbDX3WDl5Sk83Wlg4ODA">
                            <p class="text-size-wrap">GS ТЕХНОПОЛИС 13.08.2017 Триатлон спринт GS</p>
                            <img class="img-fluid rounded" src="./img/sprintGS.jpg">
                        </a>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="pb-5 pt-5 text-light bg-dark">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    Исходники лежат на <a class="btn-link text-white" href="https://github.com/VadimCpp/club111-landing"><u>Github</u></a>
                </div>
            </div>
        </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
   
  },
  methods: {
    onTop: function() {
      window.location.href = "#"
    }
  }
}
</script>

<style>
:root {
    --lh: 1.4rem;
  }

html {
    scroll-behavior: smooth;
}

.bg-even {
    background-color: rgb(230, 230, 230);
}

.btn-wrap {
    word-break: break-word;
    white-space: normal;
}

#go-top {
    /* display: none; */
    position: fixed;
    bottom: 20px;
    right: 20px;
    z-index: 2;
}

.navbar {
    border-bottom: 1px solid rgba(204, 204, 204, 0);
    transition-duration: 0.3s;
}

.border-b {
    border-bottom: 1px solid rgba(204, 204, 204, 1);
    transition-duration: 0.3s;
}

.text-box {
    line-height: var(--lh);
}

/* Ref: https://stackoverflow.com/a/19049457/1775459 */
.text-size-wrap {
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
    height: 45px;
    margin-top: 15px;
    margin-bottom: 5px;
}
</style>
