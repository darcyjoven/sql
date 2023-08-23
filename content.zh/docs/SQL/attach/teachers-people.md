---
title: "插入people和teachers"
weight: 10
tags: ["SQL"]
categories: ["SQL"]
# bookComments: false
# bookSearchExclude: false
---

# 插入 people 和 teachers

## people

```

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('王锐达', 1, to_date('02-01-1970', 'dd-mm-yyyy'), 14000000000, '漳平', '123456789012345005', to_date('02-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李元德', 1, to_date('03-01-1970', 'dd-mm-yyyy'), 14000000001, '福安', '123456789012345006', to_date('03-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑承弼', 1, to_date('04-01-1970', 'dd-mm-yyyy'), 14000000002, '福鼎', '123456789012345007', to_date('04-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张勇毅', 1, to_date('05-01-1970', 'dd-mm-yyyy'), 14000000003, '兰州', '123456789012345008', to_date('05-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吴同济', 1, to_date('06-01-1970', 'dd-mm-yyyy'), 14000000004, '嘉峪关', '123456789012345009', to_date('06-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈志义', 1, to_date('07-01-1970', 'dd-mm-yyyy'), 14000000005, '金昌', '123456789012345010', to_date('07-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱鸿远', 1, to_date('08-01-1970', 'dd-mm-yyyy'), 14000000006, '白银', '123456789012345011', to_date('08-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒋宜人', 1, to_date('09-01-1970', 'dd-mm-yyyy'), 14000000007, '天水', '123456789012345012', to_date('09-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒋明德', 1, to_date('10-01-1970', 'dd-mm-yyyy'), 14000000008, '酒泉', '123456789012345013', to_date('10-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙阳嘉', 1, to_date('11-01-1970', 'dd-mm-yyyy'), 14000000009, '张掖', '123456789012345014', to_date('11-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏康时', 1, to_date('12-01-1970', 'dd-mm-yyyy'), 14000000010, '武威', '123456789012345015', to_date('12-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杨力勤', 1, to_date('13-01-1970', 'dd-mm-yyyy'), 14000000011, '庆阳', '123456789012345016', to_date('13-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏宏朗', 1, to_date('14-01-1970', 'dd-mm-yyyy'), 14000000012, '平凉', '123456789012345017', to_date('14-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑建树', 1, to_date('15-01-1970', 'dd-mm-yyyy'), 14000000013, '定西', '123456789012345018', to_date('15-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏成济', 1, to_date('16-01-1970', 'dd-mm-yyyy'), 14000000014, '陇南', '123456789012345019', to_date('16-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈俊迈', 1, to_date('17-01-1970', 'dd-mm-yyyy'), 14000000015, '玉门', '123456789012345020', to_date('17-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张英叡', 1, to_date('18-01-1970', 'dd-mm-yyyy'), 14000000016, '敦煌', '123456789012345021', to_date('18-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('楚俊侠', 1, to_date('19-01-1970', 'dd-mm-yyyy'), 14000000017, '临夏', '123456789012345022', to_date('19-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周翰采', 1, to_date('20-01-1970', 'dd-mm-yyyy'), 14000000018, '合作', '123456789012345023', to_date('20-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵嘉祯', 1, to_date('21-01-1970', 'dd-mm-yyyy'), 14000000019, '级城市', '123456789012345024', to_date('21-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯天干', 1, to_date('22-01-1970', 'dd-mm-yyyy'), 14000000020, '级城市', '123456789012345025', to_date('22-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈涵亮', 1, to_date('23-01-1970', 'dd-mm-yyyy'), 14000000021, '清远', '123456789012345026', to_date('23-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩俊智', 1, to_date('24-01-1970', 'dd-mm-yyyy'), 14000000022, '韶关', '123456789012345027', to_date('24-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏明达', 1, to_date('25-01-1970', 'dd-mm-yyyy'), 14000000023, '河源', '123456789012345028', to_date('25-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵鸿哲', 1, to_date('26-01-1970', 'dd-mm-yyyy'), 14000000024, '梅州', '123456789012345029', to_date('26-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关英喆', 1, to_date('27-01-1970', 'dd-mm-yyyy'), 14000000025, '潮州', '123456789012345030', to_date('27-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周经纶', 1, to_date('28-01-1970', 'dd-mm-yyyy'), 14000000026, '汕头', '123456789012345031', to_date('28-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱浩言', 1, to_date('29-01-1970', 'dd-mm-yyyy'), 14000000027, '揭阳', '123456789012345032', to_date('29-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈锐藻', 1, to_date('30-01-1970', 'dd-mm-yyyy'), 14000000028, '汕尾', '123456789012345033', to_date('30-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑哲瀚', 1, to_date('31-01-1970', 'dd-mm-yyyy'), 14000000029, '惠州', '123456789012345034', to_date('31-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('刘星洲', 1, to_date('01-02-1970', 'dd-mm-yyyy'), 14000000030, '东莞', '123456789012345035', to_date('01-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('王正德', 1, to_date('02-02-1970', 'dd-mm-yyyy'), 14000000031, '珠海', '123456789012345036', to_date('02-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑奇迈', 1, to_date('03-02-1970', 'dd-mm-yyyy'), 14000000032, '中山', '123456789012345037', to_date('03-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈经纶', 1, to_date('04-02-1970', 'dd-mm-yyyy'), 14000000033, '江门', '123456789012345038', to_date('04-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周涵衍', 1, to_date('05-02-1970', 'dd-mm-yyyy'), 14000000034, '佛山', '123456789012345039', to_date('05-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李彭祖', 1, to_date('06-02-1970', 'dd-mm-yyyy'), 14000000035, '肇庆', '123456789012345040', to_date('06-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈鸿雪', 1, to_date('07-02-1970', 'dd-mm-yyyy'), 14000000036, '云浮', '123456789012345041', to_date('07-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周文成', 1, to_date('08-02-1970', 'dd-mm-yyyy'), 14000000037, '阳江', '123456789012345042', to_date('08-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵英悟', 1, to_date('09-02-1970', 'dd-mm-yyyy'), 14000000038, '茂名', '123456789012345043', to_date('09-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏宏硕', 1, to_date('10-02-1970', 'dd-mm-yyyy'), 14000000039, '湛江', '123456789012345044', to_date('10-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周才哲', 1, to_date('11-02-1970', 'dd-mm-yyyy'), 14000000040, '从化', '123456789012345045', to_date('11-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙天纵', 1, to_date('12-02-1970', 'dd-mm-yyyy'), 14000000041, '增城', '123456789012345046', to_date('12-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杨奇逸', 1, to_date('13-02-1970', 'dd-mm-yyyy'), 14000000042, '英德', '123456789012345047', to_date('13-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯经业', 1, to_date('14-02-1970', 'dd-mm-yyyy'), 14000000043, '连州', '123456789012345048', to_date('14-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑睿明', 1, to_date('15-02-1970', 'dd-mm-yyyy'), 14000000044, '乐昌', '123456789012345049', to_date('15-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵博容', 1, to_date('16-02-1970', 'dd-mm-yyyy'), 14000000045, '南雄', '123456789012345050', to_date('16-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈咏志', 1, to_date('17-02-1970', 'dd-mm-yyyy'), 14000000046, '兴宁', '123456789012345051', to_date('17-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('刘咏思', 1, to_date('18-02-1970', 'dd-mm-yyyy'), 14000000047, '普宁', '123456789012345052', to_date('18-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵昊乾', 1, to_date('19-02-1970', 'dd-mm-yyyy'), 14000000048, '陆丰', '123456789012345053', to_date('19-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯茂学', 1, to_date('20-02-1970', 'dd-mm-yyyy'), 14000000049, '恩平', '123456789012345054', to_date('20-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒋冰双', 2, to_date('21-02-1970', 'dd-mm-yyyy'), 14000000050, '台山', '123456789012345055', to_date('21-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈冰烟', 2, to_date('22-02-1970', 'dd-mm-yyyy'), 14000000051, '开平', '123456789012345056', to_date('22-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周天巧', 2, to_date('23-02-1970', 'dd-mm-yyyy'), 14000000052, '鹤山', '123456789012345057', to_date('23-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏美怡', 2, to_date('24-02-1970', 'dd-mm-yyyy'), 14000000053, '高要', '123456789012345058', to_date('24-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关芷蕾', 2, to_date('25-02-1970', 'dd-mm-yyyy'), 14000000054, '四会', '123456789012345059', to_date('25-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯英慧', 2, to_date('26-02-1970', 'dd-mm-yyyy'), 14000000055, '罗定', '123456789012345060', to_date('26-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杨梦蕾', 2, to_date('27-02-1970', 'dd-mm-yyyy'), 14000000056, '阳春', '123456789012345061', to_date('27-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩冬亦', 2, to_date('28-02-1970', 'dd-mm-yyyy'), 14000000057, '化州', '123456789012345062', to_date('28-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吴秋荣', 2, to_date('01-03-1970', 'dd-mm-yyyy'), 14000000058, '信宜', '123456789012345063', to_date('01-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱燕晓', 2, to_date('02-03-1970', 'dd-mm-yyyy'), 14000000059, '高州', '123456789012345064', to_date('02-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('楚桃粉', 2, to_date('03-03-1970', 'dd-mm-yyyy'), 14000000060, '吴川', '123456789012345065', to_date('03-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周柳思', 2, to_date('04-03-1970', 'dd-mm-yyyy'), 14000000061, '廉江', '123456789012345066', to_date('04-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张博丽', 2, to_date('05-03-1970', 'dd-mm-yyyy'), 14000000062, '雷州', '123456789012345067', to_date('05-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯芮优', 2, to_date('06-03-1970', 'dd-mm-yyyy'), 14000000063, '贵阳', '123456789012345068', to_date('06-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩三诗', 2, to_date('07-03-1970', 'dd-mm-yyyy'), 14000000064, '六盘水', '123456789012345069', to_date('07-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李晓巧', 2, to_date('08-03-1970', 'dd-mm-yyyy'), 14000000065, '遵义', '123456789012345070', to_date('08-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张曼凝', 2, to_date('09-03-1970', 'dd-mm-yyyy'), 14000000066, '安顺', '123456789012345071', to_date('09-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱夏璇', 2, to_date('10-03-1970', 'dd-mm-yyyy'), 14000000067, '毕节', '123456789012345072', to_date('10-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩燕妮', 2, to_date('11-03-1970', 'dd-mm-yyyy'), 14000000068, '铜仁', '123456789012345073', to_date('11-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑玲芬', 2, to_date('12-03-1970', 'dd-mm-yyyy'), 14000000069, '清镇', '123456789012345074', to_date('12-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩雁风', 2, to_date('13-03-1970', 'dd-mm-yyyy'), 14000000070, '赤水', '123456789012345075', to_date('13-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈香馨', 2, to_date('14-03-1970', 'dd-mm-yyyy'), 14000000071, '仁怀', '123456789012345076', to_date('14-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张蕴美', 2, to_date('15-03-1970', 'dd-mm-yyyy'), 14000000072, '凯里', '123456789012345077', to_date('15-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱霞雰', 2, to_date('16-03-1970', 'dd-mm-yyyy'), 14000000073, '都匀', '123456789012345078', to_date('16-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩国萍', 2, to_date('17-03-1970', 'dd-mm-yyyy'), 14000000074, '兴义', '123456789012345079', to_date('17-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('楚傲白', 2, to_date('18-03-1970', 'dd-mm-yyyy'), 14000000075, '福泉', '123456789012345080', to_date('18-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李白桃', 2, to_date('19-03-1970', 'dd-mm-yyyy'), 14000000076, '石家庄', '123456789012345081', to_date('19-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周束芳', 2, to_date('20-03-1970', 'dd-mm-yyyy'), 14000000077, '邯郸', '123456789012345082', to_date('20-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑蔡琳', 2, to_date('21-03-1970', 'dd-mm-yyyy'), 14000000078, '唐山', '123456789012345083', to_date('21-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵红美', 2, to_date('22-03-1970', 'dd-mm-yyyy'), 14000000079, '保定', '123456789012345084', to_date('22-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑丹珍', 2, to_date('23-03-1970', 'dd-mm-yyyy'), 14000000080, '秦皇岛', '123456789012345085', to_date('23-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关琇晶', 2, to_date('24-03-1970', 'dd-mm-yyyy'), 14000000081, '邢台', '123456789012345086', to_date('24-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒋晓星', 2, to_date('25-03-1970', 'dd-mm-yyyy'), 14000000082, '张家口', '123456789012345087', to_date('25-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关安青', 2, to_date('26-03-1970', 'dd-mm-yyyy'), 14000000083, '承德', '123456789012345088', to_date('26-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏丹烟', 2, to_date('27-03-1970', 'dd-mm-yyyy'), 14000000084, '沧州', '123456789012345089', to_date('27-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏斐斐', 2, to_date('28-03-1970', 'dd-mm-yyyy'), 14000000085, '廊坊', '123456789012345090', to_date('28-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩丽芳', 2, to_date('29-03-1970', 'dd-mm-yyyy'), 14000000086, '衡水', '123456789012345091', to_date('29-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑傲白', 2, to_date('30-03-1970', 'dd-mm-yyyy'), 14000000087, '辛集', '123456789012345092', to_date('30-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吴惜萱', 2, to_date('31-03-1970', 'dd-mm-yyyy'), 14000000088, '藁城', '123456789012345093', to_date('31-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵皓洁', 2, to_date('01-04-1970', 'dd-mm-yyyy'), 14000000089, '晋州', '123456789012345094', to_date('01-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯倩冰', 2, to_date('02-04-1970', 'dd-mm-yyyy'), 14000000090, '新乐', '123456789012345095', to_date('02-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩兰月', 2, to_date('03-04-1970', 'dd-mm-yyyy'), 14000000091, '鹿泉', '123456789012345096', to_date('03-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周泽惠', 2, to_date('04-04-1970', 'dd-mm-yyyy'), 14000000092, '遵化', '123456789012345097', to_date('04-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱清浅', 2, to_date('05-04-1970', 'dd-mm-yyyy'), 14000000093, '迁安', '123456789012345098', to_date('05-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杨嘉歆', 2, to_date('06-04-1970', 'dd-mm-yyyy'), 14000000094, '霸州', '123456789012345099', to_date('06-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关云岚', 2, to_date('07-04-1970', 'dd-mm-yyyy'), 14000000095, '三河', '123456789012345100', to_date('07-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑含莲', 2, to_date('08-04-1970', 'dd-mm-yyyy'), 14000000096, '定州', '123456789012345101', to_date('08-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张语冰', 2, to_date('09-04-1970', 'dd-mm-yyyy'), 14000000097, '涿州', '123456789012345102', to_date('09-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑真文', 2, to_date('10-04-1970', 'dd-mm-yyyy'), 14000000098, '安国', '123456789012345103', to_date('10-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈曼珠', 2, to_date('11-04-1970', 'dd-mm-yyyy'), 14000000099, '高碑店', '123456789012345104', to_date('11-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯斌', 1, to_date('12-04-1970', 'dd-mm-yyyy'), 14000000100, '泊头', '123456789012345105', to_date('12-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙益', 1, to_date('13-04-1970', 'dd-mm-yyyy'), 14000000101, '任丘', '123456789012345106', to_date('13-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('刘仑', 1, to_date('14-04-1970', 'dd-mm-yyyy'), 14000000102, '黄骅', '123456789012345107', to_date('14-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关圣', 1, to_date('15-04-1970', 'dd-mm-yyyy'), 14000000103, '河间', '123456789012345108', to_date('15-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('印景辉', 2, to_date('16-11-2002', 'dd-mm-yyyy'), 14000000319, '旅顺', '123456789012355132', to_date('16-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('龚敏智', 2, to_date('12-02-2002', 'dd-mm-yyyy'), 14000000320, '旅顺', '123456789012355133', to_date('17-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宓建同', 2, to_date('22-06-2002', 'dd-mm-yyyy'), 14000000321, '旅顺', '123456789012355134', to_date('18-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郗景天', 2, to_date('11-03-2002', 'dd-mm-yyyy'), 14000000322, '旅顺', '123456789012355135', to_date('19-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('曹宜民', 2, to_date('07-03-2002', 'dd-mm-yyyy'), 14000000323, '旅顺', '123456789012355136', to_date('20-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱建树', 2, to_date('31-08-2001', 'dd-mm-yyyy'), 14000000324, '旅顺', '123456789012355137', to_date('21-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('聂建义', 2, to_date('05-02-2001', 'dd-mm-yyyy'), 14000000325, '旅顺', '123456789012355138', to_date('22-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钟建中', 2, to_date('19-12-2002', 'dd-mm-yyyy'), 14000000326, '旅顺', '123456789012355139', to_date('23-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('盖华辉', 2, to_date('11-05-2001', 'dd-mm-yyyy'), 14000000327, '旅顺', '123456789012355140', to_date('24-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杜高达', 2, to_date('01-10-2002', 'dd-mm-yyyy'), 14000000328, '旅顺', '123456789012355141', to_date('25-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陆展鹏', 2, to_date('17-03-2002', 'dd-mm-yyyy'), 14000000329, '旅顺', '123456789012355142', to_date('26-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阎学林', 2, to_date('11-10-2001', 'dd-mm-yyyy'), 14000000330, '旅顺', '123456789012355143', to_date('27-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈彭泽', 2, to_date('09-07-2001', 'dd-mm-yyyy'), 14000000331, '旅顺', '123456789012355144', to_date('28-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('麴俊迈', 2, to_date('03-12-2002', 'dd-mm-yyyy'), 14000000332, '旅顺', '123456789012355145', to_date('29-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('容振海', 2, to_date('26-04-2002', 'dd-mm-yyyy'), 14000000333, '旅顺', '123456789012355146', to_date('30-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒲正真', 2, to_date('26-02-2001', 'dd-mm-yyyy'), 14000000334, '旅顺', '123456789012355147', to_date('01-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('侯安宁', 2, to_date('09-06-2001', 'dd-mm-yyyy'), 14000000335, '旅顺', '123456789012355148', to_date('02-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('暨天赋', 2, to_date('15-07-2001', 'dd-mm-yyyy'), 14000000336, '旅顺', '123456789012355149', to_date('03-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('乌睿思', 2, to_date('09-04-2001', 'dd-mm-yyyy'), 14000000337, '旅顺', '123456789012355150', to_date('04-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('尚高峰', 2, to_date('25-09-2001', 'dd-mm-yyyy'), 14000000338, '旅顺', '123456789012355151', to_date('05-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('林阳夏', 2, to_date('27-02-2002', 'dd-mm-yyyy'), 14000000339, '旅顺', '123456789012355152', to_date('06-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('芮弘大', 2, to_date('25-10-2001', 'dd-mm-yyyy'), 14000000340, '旅顺', '123456789012355153', to_date('07-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宁志明', 2, to_date('14-08-2002', 'dd-mm-yyyy'), 14000000341, '旅顺', '123456789012355154', to_date('08-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('璩开济', 2, to_date('14-06-2001', 'dd-mm-yyyy'), 14000000342, '旅顺', '123456789012355155', to_date('09-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('邴子平', 2, to_date('14-08-2001', 'dd-mm-yyyy'), 14000000343, '旅顺', '123456789012355156', to_date('10-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏正谊', 2, to_date('29-09-2002', 'dd-mm-yyyy'), 14000000344, '旅顺', '123456789012355157', to_date('11-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冉乐语', 2, to_date('21-08-2002', 'dd-mm-yyyy'), 14000000345, '旅顺', '123456789012355158', to_date('12-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('屠明德', 2, to_date('16-08-2002', 'dd-mm-yyyy'), 14000000346, '旅顺', '123456789012355159', to_date('13-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钭泰初', 2, to_date('25-09-2001', 'dd-mm-yyyy'), 14000000347, '旅顺', '123456789012355160', to_date('14-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('党浩慨', 2, to_date('03-01-2002', 'dd-mm-yyyy'), 14000000348, '旅顺', '123456789012355161', to_date('15-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('黎高义', 2, to_date('17-05-2002', 'dd-mm-yyyy'), 14000000349, '旅顺', '123456789012355162', to_date('16-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒙明志', 2, to_date('14-04-2001', 'dd-mm-yyyy'), 14000000350, '旅顺', '123456789012355163', to_date('17-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('甄浩言', 2, to_date('18-05-2001', 'dd-mm-yyyy'), 14000000351, '旅顺', '123456789012355164', to_date('18-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宿明志', 2, to_date('24-06-2001', 'dd-mm-yyyy'), 14000000352, '旅顺', '123456789012355165', to_date('19-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('连瑾瑜', 2, to_date('21-04-2001', 'dd-mm-yyyy'), 14000000353, '旅顺', '123456789012355166', to_date('20-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('任浩初', 2, to_date('22-05-2001', 'dd-mm-yyyy'), 14000000354, '旅顺', '123456789012355167', to_date('21-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('容华奥', 2, to_date('28-07-2002', 'dd-mm-yyyy'), 14000000355, '旅顺', '123456789012355168', to_date('22-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('暨志泽', 2, to_date('27-07-2001', 'dd-mm-yyyy'), 14000000356, '旅顺', '123456789012355169', to_date('23-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('容永宁', 2, to_date('12-01-2001', 'dd-mm-yyyy'), 14000000357, '旅顺', '123456789012355170', to_date('24-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郜飞白', 2, to_date('11-04-2002', 'dd-mm-yyyy'), 14000000358, '旅顺', '123456789012355171', to_date('25-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关正平', 2, to_date('17-05-2002', 'dd-mm-yyyy'), 14000000359, '旅顺', '123456789012355172', to_date('26-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杜俊喆', 2, to_date('13-04-2002', 'dd-mm-yyyy'), 14000000360, '旅顺', '123456789012355173', to_date('27-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('耿承悦', 2, to_date('25-07-2001', 'dd-mm-yyyy'), 14000000361, '旅顺', '123456789012355174', to_date('28-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('牛志义', 2, to_date('20-08-2002', 'dd-mm-yyyy'), 14000000362, '旅顺', '123456789012355175', to_date('29-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郜浩淼', 2, to_date('14-08-2001', 'dd-mm-yyyy'), 14000000363, '旅顺', '123456789012355176', to_date('30-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('白泰然', 2, to_date('08-04-2002', 'dd-mm-yyyy'), 14000000364, '旅顺', '123456789012355177', to_date('31-12-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吕宏远', 2, to_date('24-09-2001', 'dd-mm-yyyy'), 14000000365, '旅顺', '123456789012355178', to_date('01-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郁俊侠', 2, to_date('16-04-2002', 'dd-mm-yyyy'), 14000000366, '旅顺', '123456789012355179', to_date('02-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('满子实', 2, to_date('05-02-2002', 'dd-mm-yyyy'), 14000000367, '旅顺', '123456789012355180', to_date('03-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钟彬炳', 2, to_date('03-07-2001', 'dd-mm-yyyy'), 14000000368, '旅顺', '123456789012355181', to_date('04-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阚翰飞', 2, to_date('31-01-2002', 'dd-mm-yyyy'), 14000000369, '旅顺', '123456789012355182', to_date('05-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('索英喆', 2, to_date('09-11-2001', 'dd-mm-yyyy'), 14000000370, '旅顺', '123456789012355183', to_date('06-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('林信鸥', 2, to_date('11-01-2002', 'dd-mm-yyyy'), 14000000371, '旅顺', '123456789012355184', to_date('07-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('隗华灿', 2, to_date('26-02-2002', 'dd-mm-yyyy'), 14000000372, '旅顺', '123456789012355185', to_date('08-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('利乐家', 2, to_date('08-06-2002', 'dd-mm-yyyy'), 14000000373, '旅顺', '123456789012355186', to_date('09-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阴思聪', 2, to_date('17-06-2001', 'dd-mm-yyyy'), 14000000374, '旅顺', '123456789012355187', to_date('10-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('怀乐意', 2, to_date('28-03-2001', 'dd-mm-yyyy'), 14000000375, '旅顺', '123456789012355188', to_date('11-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('充德本', 2, to_date('26-11-2002', 'dd-mm-yyyy'), 14000000376, '旅顺', '123456789012355189', to_date('12-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蔡宏远', 2, to_date('28-03-2002', 'dd-mm-yyyy'), 14000000377, '旅顺', '123456789012355190', to_date('13-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郏嘉胜', 2, to_date('08-03-2002', 'dd-mm-yyyy'), 14000000378, '旅顺', '123456789012355191', to_date('14-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('万英彦', 2, to_date('23-05-2001', 'dd-mm-yyyy'), 14000000379, '旅顺', '123456789012355192', to_date('15-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('贺兴文', 2, to_date('01-10-2002', 'dd-mm-yyyy'), 14000000380, '旅顺', '123456789012355193', to_date('16-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郗温书', 2, to_date('14-05-2002', 'dd-mm-yyyy'), 14000000381, '旅顺', '123456789012355194', to_date('17-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沃俊达', 2, to_date('29-04-2002', 'dd-mm-yyyy'), 14000000382, '旅顺', '123456789012355195', to_date('18-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('鱼兴文', 2, to_date('09-09-2001', 'dd-mm-yyyy'), 14000000383, '旅顺', '123456789012355196', to_date('19-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('熊元驹', 2, to_date('08-05-2002', 'dd-mm-yyyy'), 14000000384, '旅顺', '123456789012355197', to_date('20-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('农博裕', 2, to_date('28-12-2001', 'dd-mm-yyyy'), 14000000385, '旅顺', '123456789012355198', to_date('21-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('相文曜', 2, to_date('15-11-2002', 'dd-mm-yyyy'), 14000000386, '旅顺', '123456789012355199', to_date('22-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('温鸿畅', 2, to_date('16-03-2002', 'dd-mm-yyyy'), 14000000387, '旅顺', '123456789012355200', to_date('23-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒋元凯', 2, to_date('04-08-2002', 'dd-mm-yyyy'), 14000000388, '旅顺', '123456789012355201', to_date('24-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('潘元甲', 2, to_date('25-05-2002', 'dd-mm-yyyy'), 14000000389, '旅顺', '123456789012355202', to_date('25-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宦俊悟', 2, to_date('13-11-2001', 'dd-mm-yyyy'), 14000000390, '旅顺', '123456789012355203', to_date('26-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('侯兴朝', 2, to_date('30-04-2002', 'dd-mm-yyyy'), 14000000391, '旅顺', '123456789012355204', to_date('27-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('巢景焕', 2, to_date('28-05-2002', 'dd-mm-yyyy'), 14000000392, '旅顺', '123456789012355205', to_date('28-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩永福', 2, to_date('02-06-2002', 'dd-mm-yyyy'), 14000000393, '旅顺', '123456789012355206', to_date('29-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张永昌', 2, to_date('19-11-2002', 'dd-mm-yyyy'), 14000000394, '旅顺', '123456789012355207', to_date('30-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('庄高扬', 2, to_date('08-02-2002', 'dd-mm-yyyy'), 14000000395, '旅顺', '123456789012355208', to_date('31-01-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('濮浩大', 2, to_date('06-11-2001', 'dd-mm-yyyy'), 14000000396, '旅顺', '123456789012355209', to_date('01-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('弘伟茂', 2, to_date('02-09-2002', 'dd-mm-yyyy'), 14000000397, '旅顺', '123456789012355210', to_date('02-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('康鸿波', 2, to_date('12-02-2002', 'dd-mm-yyyy'), 14000000398, '旅顺', '123456789012355211', to_date('03-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蔚绍钧', 2, to_date('22-08-2001', 'dd-mm-yyyy'), 14000000399, '旅顺', '123456789012355212', to_date('04-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宫安顺', 2, to_date('15-05-2001', 'dd-mm-yyyy'), 14000000400, '旅顺', '123456789012355213', to_date('05-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('邰子晋', 2, to_date('29-04-2001', 'dd-mm-yyyy'), 14000000401, '旅顺', '123456789012355214', to_date('06-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('须和泰', 2, to_date('04-04-2001', 'dd-mm-yyyy'), 14000000402, '旅顺', '123456789012355215', to_date('07-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('游德华', 2, to_date('06-11-2002', 'dd-mm-yyyy'), 14000000403, '旅顺', '123456789012355216', to_date('08-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('雍安易', 2, to_date('03-10-2001', 'dd-mm-yyyy'), 14000000404, '旅顺', '123456789012355217', to_date('09-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('漕明达', 2, to_date('03-08-2002', 'dd-mm-yyyy'), 14000000405, '旅顺', '123456789012355218', to_date('10-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙嘉年', 2, to_date('26-01-2001', 'dd-mm-yyyy'), 14000000406, '旅顺', '123456789012355219', to_date('11-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('边元忠', 2, to_date('15-10-2002', 'dd-mm-yyyy'), 14000000407, '旅顺', '123456789012355220', to_date('12-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('晃康平', 2, to_date('16-03-2002', 'dd-mm-yyyy'), 14000000408, '旅顺', '123456789012355221', to_date('13-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('漕奇思', 2, to_date('12-02-2002', 'dd-mm-yyyy'), 14000000409, '旅顺', '123456789012355222', to_date('14-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吴凯泽', 2, to_date('08-10-2002', 'dd-mm-yyyy'), 14000000410, '旅顺', '123456789012355223', to_date('15-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('江阳曜', 2, to_date('31-03-2002', 'dd-mm-yyyy'), 14000000411, '旅顺', '123456789012355224', to_date('16-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵同化', 2, to_date('14-09-2002', 'dd-mm-yyyy'), 14000000412, '旅顺', '123456789012355225', to_date('17-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('屠哲茂', 2, to_date('01-04-2001', 'dd-mm-yyyy'), 14000000413, '旅顺', '123456789012355226', to_date('18-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('红逸仙', 2, to_date('26-04-2002', 'dd-mm-yyyy'), 14000000414, '旅顺', '123456789012355227', to_date('19-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('毋宏富', 2, to_date('11-03-2001', 'dd-mm-yyyy'), 14000000415, '旅顺', '123456789012355228', to_date('20-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('苍凯复', 2, to_date('30-08-2002', 'dd-mm-yyyy'), 14000000416, '旅顺', '123456789012355229', to_date('21-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('董意蕴', 2, to_date('29-12-2002', 'dd-mm-yyyy'), 14000000417, '旅顺', '123456789012355230', to_date('22-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏嘉歆', 2, to_date('26-06-2002', 'dd-mm-yyyy'), 14000000418, '旅顺', '123456789012355231', to_date('23-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('盖欣荣', 2, to_date('21-02-2002', 'dd-mm-yyyy'), 14000000419, '旅顺', '123456789012355232', to_date('24-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈嘉德', 2, to_date('14-06-2002', 'dd-mm-yyyy'), 14000000420, '旅顺', '123456789012355233', to_date('25-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵高懿', 2, to_date('19-02-2001', 'dd-mm-yyyy'), 14000000421, '旅顺', '123456789012355234', to_date('26-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('顾锐泽', 2, to_date('03-02-2001', 'dd-mm-yyyy'), 14000000422, '旅顺', '123456789012355235', to_date('27-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李宏胜', 2, to_date('15-07-2002', 'dd-mm-yyyy'), 14000000423, '旅顺', '123456789012355236', to_date('28-02-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('芮文彦', 2, to_date('14-03-2002', 'dd-mm-yyyy'), 14000000424, '旅顺', '123456789012355237', to_date('01-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蓟康安', 2, to_date('08-09-2001', 'dd-mm-yyyy'), 14000000425, '旅顺', '123456789012355238', to_date('02-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宁光远', 2, to_date('07-04-2001', 'dd-mm-yyyy'), 14000000426, '旅顺', '123456789012355239', to_date('03-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冷斯年', 2, to_date('21-04-2002', 'dd-mm-yyyy'), 14000000427, '旅顺', '123456789012355240', to_date('04-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('仰玉宇', 2, to_date('21-10-2002', 'dd-mm-yyyy'), 14000000428, '旅顺', '123456789012355241', to_date('05-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冀嘉许', 2, to_date('05-01-2001', 'dd-mm-yyyy'), 14000000429, '旅顺', '123456789012355242', to_date('06-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('融宏伟', 2, to_date('01-01-2003', 'dd-mm-yyyy'), 14000000430, '旅顺', '123456789012355243', to_date('07-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杜鸿羲', 2, to_date('25-07-2002', 'dd-mm-yyyy'), 14000000431, '旅顺', '123456789012355244', to_date('08-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('崔学义', 2, to_date('07-04-2002', 'dd-mm-yyyy'), 14000000432, '旅顺', '123456789012355245', to_date('09-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孟宏儒', 2, to_date('11-07-2002', 'dd-mm-yyyy'), 14000000433, '旅顺', '123456789012355246', to_date('10-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阴坚诚', 2, to_date('29-01-2002', 'dd-mm-yyyy'), 14000000434, '旅顺', '123456789012355247', to_date('11-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('相德元', 2, to_date('08-04-2001', 'dd-mm-yyyy'), 14000000435, '旅顺', '123456789012355248', to_date('12-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('红宏茂', 2, to_date('30-03-2001', 'dd-mm-yyyy'), 14000000436, '旅顺', '123456789012355249', to_date('13-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郏永贞', 2, to_date('01-03-2002', 'dd-mm-yyyy'), 14000000437, '旅顺', '123456789012355250', to_date('14-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒋元基', 2, to_date('14-10-2001', 'dd-mm-yyyy'), 14000000438, '旅顺', '123456789012355251', to_date('15-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒯嘉荣', 2, to_date('20-02-2002', 'dd-mm-yyyy'), 14000000439, '旅顺', '123456789012355252', to_date('16-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('寇同化', 2, to_date('21-06-2001', 'dd-mm-yyyy'), 14000000440, '旅顺', '123456789012355253', to_date('17-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('璩涵润', 2, to_date('10-05-2002', 'dd-mm-yyyy'), 14000000441, '旅顺', '123456789012355254', to_date('18-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('籍彭越', 2, to_date('26-06-2002', 'dd-mm-yyyy'), 14000000442, '旅顺', '123456789012355255', to_date('19-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('戴明轩', 2, to_date('22-10-2001', 'dd-mm-yyyy'), 14000000443, '旅顺', '123456789012355256', to_date('20-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('车华藏', 2, to_date('09-08-2001', 'dd-mm-yyyy'), 14000000444, '旅顺', '123456789012355257', to_date('21-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('扈光霁', 2, to_date('18-04-2002', 'dd-mm-yyyy'), 14000000445, '旅顺', '123456789012355258', to_date('22-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钟良朋', 2, to_date('08-02-2002', 'dd-mm-yyyy'), 14000000446, '旅顺', '123456789012355259', to_date('23-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('习炎彬', 2, to_date('26-04-2002', 'dd-mm-yyyy'), 14000000447, '旅顺', '123456789012355260', to_date('24-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('贡安澜', 2, to_date('27-05-2002', 'dd-mm-yyyy'), 14000000448, '旅顺', '123456789012355261', to_date('25-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('苏文虹', 2, to_date('05-06-2002', 'dd-mm-yyyy'), 14000000449, '旅顺', '123456789012355262', to_date('26-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('家鹏天', 2, to_date('15-08-2001', 'dd-mm-yyyy'), 14000000450, '旅顺', '123456789012355263', to_date('27-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('居文敏', 2, to_date('05-09-2002', 'dd-mm-yyyy'), 14000000451, '旅顺', '123456789012355264', to_date('28-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('束俊艾', 2, to_date('09-05-2002', 'dd-mm-yyyy'), 14000000452, '旅顺', '123456789012355265', to_date('29-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('余和安', 2, to_date('28-05-2002', 'dd-mm-yyyy'), 14000000453, '旅顺', '123456789012355266', to_date('30-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('武刚毅', 2, to_date('28-12-2002', 'dd-mm-yyyy'), 14000000454, '旅顺', '123456789012355267', to_date('31-03-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('牛弘义', 2, to_date('07-09-2002', 'dd-mm-yyyy'), 14000000455, '旅顺', '123456789012355268', to_date('01-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('桂宏伟', 2, to_date('28-11-2002', 'dd-mm-yyyy'), 14000000456, '旅顺', '123456789012355269', to_date('02-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('燕文康', 2, to_date('01-09-2002', 'dd-mm-yyyy'), 14000000457, '旅顺', '123456789012355270', to_date('03-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('仰鸿运', 2, to_date('23-05-2001', 'dd-mm-yyyy'), 14000000458, '旅顺', '123456789012355271', to_date('04-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑睿思', 2, to_date('20-10-2001', 'dd-mm-yyyy'), 14000000459, '旅顺', '123456789012355272', to_date('05-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('甄乐康', 2, to_date('13-01-2001', 'dd-mm-yyyy'), 14000000460, '旅顺', '123456789012355273', to_date('06-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('游晗昱', 2, to_date('01-07-2002', 'dd-mm-yyyy'), 14000000461, '旅顺', '123456789012355274', to_date('07-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冉兴旺', 2, to_date('22-12-2002', 'dd-mm-yyyy'), 14000000462, '旅顺', '123456789012355275', to_date('08-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('漕浩波', 2, to_date('15-09-2002', 'dd-mm-yyyy'), 14000000463, '旅顺', '123456789012355276', to_date('09-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冷才艺', 2, to_date('24-08-2001', 'dd-mm-yyyy'), 14000000464, '旅顺', '123456789012355277', to_date('10-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('索明亮', 2, to_date('02-10-2002', 'dd-mm-yyyy'), 14000000465, '旅顺', '123456789012355278', to_date('11-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('连文石', 2, to_date('28-08-2001', 'dd-mm-yyyy'), 14000000466, '旅顺', '123456789012355279', to_date('12-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宫英资', 2, to_date('04-02-2002', 'dd-mm-yyyy'), 14000000467, '旅顺', '123456789012355280', to_date('13-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('索越彬', 2, to_date('10-12-2001', 'dd-mm-yyyy'), 14000000468, '旅顺', '123456789012355281', to_date('14-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('彭子濯', 2, to_date('02-05-2001', 'dd-mm-yyyy'), 14000000469, '旅顺', '123456789012355282', to_date('15-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('寿乐悦', 2, to_date('28-03-2002', 'dd-mm-yyyy'), 14000000470, '旅顺', '123456789012355283', to_date('16-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宋安邦', 2, to_date('03-11-2002', 'dd-mm-yyyy'), 14000000471, '旅顺', '123456789012355284', to_date('17-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('丁明德', 2, to_date('07-08-2002', 'dd-mm-yyyy'), 14000000472, '旅顺', '123456789012355285', to_date('18-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('弘博涛', 2, to_date('06-10-2002', 'dd-mm-yyyy'), 14000000473, '旅顺', '123456789012355286', to_date('19-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('申涵涵', 2, to_date('04-09-2001', 'dd-mm-yyyy'), 14000000474, '旅顺', '123456789012355287', to_date('20-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('叶鹏池', 2, to_date('22-12-2001', 'dd-mm-yyyy'), 14000000475, '旅顺', '123456789012355288', to_date('21-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('简文康', 2, to_date('06-01-2001', 'dd-mm-yyyy'), 14000000476, '旅顺', '123456789012355289', to_date('22-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('融嘉泽', 2, to_date('01-01-2003', 'dd-mm-yyyy'), 14000000477, '旅顺', '123456789012355290', to_date('23-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('池斌斌', 2, to_date('03-11-2001', 'dd-mm-yyyy'), 14000000478, '旅顺', '123456789012355291', to_date('24-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('越浩宕', 2, to_date('21-06-2002', 'dd-mm-yyyy'), 14000000479, '旅顺', '123456789012355292', to_date('25-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('暴睿达', 2, to_date('29-08-2001', 'dd-mm-yyyy'), 14000000480, '旅顺', '123456789012355293', to_date('26-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('车博简', 2, to_date('31-08-2002', 'dd-mm-yyyy'), 14000000481, '旅顺', '123456789012355294', to_date('27-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('容浩穰', 2, to_date('05-11-2002', 'dd-mm-yyyy'), 14000000482, '旅顺', '123456789012355295', to_date('28-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒯巍奕', 2, to_date('04-08-2001', 'dd-mm-yyyy'), 14000000483, '旅顺', '123456789012355296', to_date('29-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杜心远', 2, to_date('08-01-2002', 'dd-mm-yyyy'), 14000000484, '旅顺', '123456789012355297', to_date('30-04-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈景焕', 2, to_date('16-04-2002', 'dd-mm-yyyy'), 14000000485, '旅顺', '123456789012355298', to_date('01-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李鸿畴', 2, to_date('31-07-2002', 'dd-mm-yyyy'), 14000000486, '旅顺', '123456789012355299', to_date('02-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杜瀚玥', 2, to_date('05-07-2001', 'dd-mm-yyyy'), 14000000487, '旅顺', '123456789012355300', to_date('03-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('终睿诚', 2, to_date('01-12-2001', 'dd-mm-yyyy'), 14000000488, '旅顺', '123456789012355301', to_date('04-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('龙文柏', 2, to_date('08-08-2001', 'dd-mm-yyyy'), 14000000489, '旅顺', '123456789012355302', to_date('05-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('满波鸿', 2, to_date('22-06-2002', 'dd-mm-yyyy'), 14000000490, '旅顺', '123456789012355303', to_date('06-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('牛德华', 2, to_date('27-04-2001', 'dd-mm-yyyy'), 14000000491, '旅顺', '123456789012355304', to_date('07-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('袁康乐', 2, to_date('23-08-2002', 'dd-mm-yyyy'), 14000000492, '旅顺', '123456789012355305', to_date('08-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('巢项明', 2, to_date('12-02-2002', 'dd-mm-yyyy'), 14000000493, '旅顺', '123456789012355306', to_date('09-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('汲开济', 2, to_date('22-09-2002', 'dd-mm-yyyy'), 14000000494, '旅顺', '123456789012355307', to_date('10-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('弘开霁', 2, to_date('24-04-2001', 'dd-mm-yyyy'), 14000000495, '旅顺', '123456789012355308', to_date('11-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('厍承嗣', 2, to_date('07-02-2002', 'dd-mm-yyyy'), 14000000496, '旅顺', '123456789012355309', to_date('12-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('殳永元', 2, to_date('27-05-2001', 'dd-mm-yyyy'), 14000000497, '旅顺', '123456789012355310', to_date('13-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('邵俊力', 2, to_date('24-10-2002', 'dd-mm-yyyy'), 14000000498, '旅顺', '123456789012355311', to_date('14-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('麴子琪', 2, to_date('02-11-2001', 'dd-mm-yyyy'), 14000000499, '旅顺', '123456789012355312', to_date('15-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('姚宜春', 2, to_date('16-10-2002', 'dd-mm-yyyy'), 14000000500, '旅顺', '123456789012355313', to_date('16-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蓬良吉', 2, to_date('17-01-2002', 'dd-mm-yyyy'), 14000000501, '旅顺', '123456789012355314', to_date('17-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('祖志新', 2, to_date('25-02-2001', 'dd-mm-yyyy'), 14000000502, '旅顺', '123456789012355315', to_date('18-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('空阳炎', 2, to_date('28-12-2002', 'dd-mm-yyyy'), 14000000503, '旅顺', '123456789012355316', to_date('19-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('卓宏深', 2, to_date('13-03-2002', 'dd-mm-yyyy'), 14000000504, '旅顺', '123456789012355317', to_date('20-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('堵嘉庆', 2, to_date('17-06-2002', 'dd-mm-yyyy'), 14000000505, '旅顺', '123456789012355318', to_date('21-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('贡嘉勋', 2, to_date('11-10-2002', 'dd-mm-yyyy'), 14000000506, '旅顺', '123456789012355319', to_date('22-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('巢烨赫', 2, to_date('08-01-2002', 'dd-mm-yyyy'), 14000000507, '旅顺', '123456789012355320', to_date('23-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('茹俊拔', 2, to_date('08-04-2002', 'dd-mm-yyyy'), 14000000508, '旅顺', '123456789012355321', to_date('24-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('伊飞龙', 2, to_date('06-12-2002', 'dd-mm-yyyy'), 14000000509, '旅顺', '123456789012355322', to_date('25-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('顾志明', 2, to_date('21-08-2001', 'dd-mm-yyyy'), 14000000510, '旅顺', '123456789012355323', to_date('26-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('终温瑜', 2, to_date('19-08-2001', 'dd-mm-yyyy'), 14000000511, '旅顺', '123456789012355324', to_date('27-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('萧和颂', 2, to_date('05-02-2001', 'dd-mm-yyyy'), 14000000512, '旅顺', '123456789012355325', to_date('28-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('闻永贞', 2, to_date('03-07-2002', 'dd-mm-yyyy'), 14000000513, '旅顺', '123456789012355326', to_date('29-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('庾蕴和', 2, to_date('04-01-2002', 'dd-mm-yyyy'), 14000000514, '旅顺', '123456789012355327', to_date('30-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('谢宏儒', 2, to_date('20-10-2001', 'dd-mm-yyyy'), 14000000515, '旅顺', '123456789012355328', to_date('31-05-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('仰乐人', 2, to_date('02-04-2001', 'dd-mm-yyyy'), 14000000516, '旅顺', '123456789012355329', to_date('01-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韶乐水', 2, to_date('30-05-2002', 'dd-mm-yyyy'), 14000000517, '旅顺', '123456789012355330', to_date('02-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('刘明旭', 2, to_date('14-12-2002', 'dd-mm-yyyy'), 14000000518, '旅顺', '123456789012355331', to_date('03-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('曾飞翰', 2, to_date('30-09-2001', 'dd-mm-yyyy'), 14000000519, '旅顺', '123456789012355332', to_date('04-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('胡宏朗', 2, to_date('22-01-2002', 'dd-mm-yyyy'), 14000000520, '旅顺', '123456789012355333', to_date('05-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('屠鸿煊', 2, to_date('24-03-2001', 'dd-mm-yyyy'), 14000000521, '旅顺', '123456789012355334', to_date('06-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('扶向笛', 2, to_date('31-07-2001', 'dd-mm-yyyy'), 14000000522, '旅顺', '123456789012355335', to_date('07-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郜奇文', 2, to_date('19-01-2001', 'dd-mm-yyyy'), 14000000523, '旅顺', '123456789012355336', to_date('08-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宁凯泽', 2, to_date('15-09-2002', 'dd-mm-yyyy'), 14000000524, '旅顺', '123456789012355337', to_date('09-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('那敏智', 2, to_date('08-04-2002', 'dd-mm-yyyy'), 14000000525, '旅顺', '123456789012355338', to_date('10-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('衡高韵', 2, to_date('09-02-2002', 'dd-mm-yyyy'), 14000000526, '旅顺', '123456789012355339', to_date('11-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('熊宇航', 2, to_date('22-11-2002', 'dd-mm-yyyy'), 14000000527, '旅顺', '123456789012355340', to_date('12-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('浦翰飞', 2, to_date('05-02-2001', 'dd-mm-yyyy'), 14000000528, '旅顺', '123456789012355341', to_date('13-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郝茂材', 2, to_date('05-06-2001', 'dd-mm-yyyy'), 14000000529, '旅顺', '123456789012355342', to_date('14-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱松', 1, to_date('16-04-1970', 'dd-mm-yyyy'), 14000000104, '冀州', '123456789012345109', to_date('16-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈峻', 1, to_date('17-04-1970', 'dd-mm-yyyy'), 14000000105, '深州', '123456789012345110', to_date('17-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱帝', 1, to_date('18-04-1970', 'dd-mm-yyyy'), 14000000106, '南宫', '123456789012345111', to_date('18-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏亮', 1, to_date('19-04-1970', 'dd-mm-yyyy'), 14000000107, '沙河', '123456789012345112', to_date('19-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周友', 1, to_date('20-04-1970', 'dd-mm-yyyy'), 14000000108, '武安', '123456789012345113', to_date('20-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏泉', 1, to_date('21-04-1970', 'dd-mm-yyyy'), 14000000109, '级城市', '123456789012345114', to_date('21-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈蔚', 1, to_date('22-04-1970', 'dd-mm-yyyy'), 14000000110, '齐齐哈尔', '123456789012345115', to_date('22-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒋杰', 1, to_date('23-04-1970', 'dd-mm-yyyy'), 14000000111, '黑河', '123456789012345116', to_date('23-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙珺', 1, to_date('24-04-1970', 'dd-mm-yyyy'), 14000000112, '大庆', '123456789012345117', to_date('24-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关有', 1, to_date('25-04-1970', 'dd-mm-yyyy'), 14000000113, '伊春', '123456789012345118', to_date('25-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杨盈', 1, to_date('26-04-1970', 'dd-mm-yyyy'), 14000000114, '鹤岗', '123456789012345119', to_date('26-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙书', 1, to_date('27-04-1970', 'dd-mm-yyyy'), 14000000115, '佳木斯', '123456789012345120', to_date('27-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张楠', 1, to_date('28-04-1970', 'dd-mm-yyyy'), 14000000116, '双鸭山', '123456789012345121', to_date('28-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张鑫', 1, to_date('29-04-1970', 'dd-mm-yyyy'), 14000000117, '七台河', '123456789012345122', to_date('29-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩承', 1, to_date('30-04-1970', 'dd-mm-yyyy'), 14000000118, '鸡西', '123456789012345123', to_date('30-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯濮', 1, to_date('01-05-1970', 'dd-mm-yyyy'), 14000000119, '牡丹江', '123456789012345124', to_date('01-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈晟', 1, to_date('02-05-1970', 'dd-mm-yyyy'), 14000000120, '绥化', '123456789012345125', to_date('02-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯汗', 1, to_date('03-05-1970', 'dd-mm-yyyy'), 14000000121, '双城', '123456789012345126', to_date('03-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙宸', 1, to_date('04-05-1970', 'dd-mm-yyyy'), 14000000122, '尚志', '123456789012345127', to_date('04-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李岩', 1, to_date('05-05-1970', 'dd-mm-yyyy'), 14000000123, '五常', '123456789012345128', to_date('05-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑仁', 1, to_date('06-05-1970', 'dd-mm-yyyy'), 14000000124, '阿城', '123456789012345129', to_date('06-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙宾', 1, to_date('07-05-1970', 'dd-mm-yyyy'), 14000000125, '讷河', '123456789012345130', to_date('07-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯荣', 1, to_date('08-05-1970', 'dd-mm-yyyy'), 14000000126, '北安', '123456789012345131', to_date('08-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('王轩', 1, to_date('09-05-1970', 'dd-mm-yyyy'), 14000000127, '五大连池', '123456789012345132', to_date('09-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈飒', 1, to_date('10-05-1970', 'dd-mm-yyyy'), 14000000128, '铁力', '123456789012345133', to_date('10-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('刘航', 1, to_date('11-05-1970', 'dd-mm-yyyy'), 14000000129, '同江', '123456789012345134', to_date('11-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏顺', 1, to_date('12-05-1970', 'dd-mm-yyyy'), 14000000130, '富锦', '123456789012345135', to_date('12-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑骞', 1, to_date('13-05-1970', 'dd-mm-yyyy'), 14000000131, '虎林', '123456789012345136', to_date('13-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱劭', 1, to_date('14-05-1970', 'dd-mm-yyyy'), 14000000132, '密山', '123456789012345137', to_date('14-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杨镰', 1, to_date('15-05-1970', 'dd-mm-yyyy'), 14000000133, '绥芬河', '123456789012345138', to_date('15-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈马', 1, to_date('16-05-1970', 'dd-mm-yyyy'), 14000000134, '海林', '123456789012345139', to_date('16-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙蔚', 1, to_date('17-05-1970', 'dd-mm-yyyy'), 14000000135, '宁安', '123456789012345140', to_date('17-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒋颇', 1, to_date('18-05-1970', 'dd-mm-yyyy'), 14000000136, '安达', '123456789012345141', to_date('18-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李亦', 1, to_date('19-05-1970', 'dd-mm-yyyy'), 14000000137, '肇东', '123456789012345142', to_date('19-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩怡', 1, to_date('20-05-1970', 'dd-mm-yyyy'), 14000000138, '海伦', '123456789012345143', to_date('20-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱博', 1, to_date('21-05-1970', 'dd-mm-yyyy'), 14000000139, '郑州', '123456789012345144', to_date('21-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙澔', 1, to_date('22-05-1970', 'dd-mm-yyyy'), 14000000140, '开封', '123456789012345145', to_date('22-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯征', 1, to_date('23-05-1970', 'dd-mm-yyyy'), 14000000141, '洛阳', '123456789012345146', to_date('23-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周轮', 1, to_date('24-05-1970', 'dd-mm-yyyy'), 14000000142, '平顶山', '123456789012345147', to_date('24-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈乒', 1, to_date('25-05-1970', 'dd-mm-yyyy'), 14000000143, '安阳', '123456789012345148', to_date('25-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张伦', 1, to_date('26-05-1970', 'dd-mm-yyyy'), 14000000144, '鹤壁', '123456789012345149', to_date('26-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵富', 1, to_date('27-05-1970', 'dd-mm-yyyy'), 14000000145, '新乡', '123456789012345150', to_date('27-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙吏', 1, to_date('28-05-1970', 'dd-mm-yyyy'), 14000000146, '焦作', '123456789012345151', to_date('28-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('刘国', 1, to_date('29-05-1970', 'dd-mm-yyyy'), 14000000147, '濮阳', '123456789012345152', to_date('29-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯倝', 1, to_date('30-05-1970', 'dd-mm-yyyy'), 14000000148, '许昌', '123456789012345153', to_date('30-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵昴', 1, to_date('31-05-1970', 'dd-mm-yyyy'), 14000000149, '漯河', '123456789012345154', to_date('31-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵莎', 2, to_date('01-06-1970', 'dd-mm-yyyy'), 14000000150, '三门峡', '123456789012345155', to_date('01-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吴星', 2, to_date('02-06-1970', 'dd-mm-yyyy'), 14000000151, '南阳', '123456789012345156', to_date('02-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙洛', 2, to_date('03-06-1970', 'dd-mm-yyyy'), 14000000152, '商丘', '123456789012345157', to_date('03-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏冬', 2, to_date('04-06-1970', 'dd-mm-yyyy'), 14000000153, '周口', '123456789012345158', to_date('04-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杨晓', 2, to_date('05-06-1970', 'dd-mm-yyyy'), 14000000154, '驻马店', '123456789012345159', to_date('05-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈玟', 2, to_date('06-06-1970', 'dd-mm-yyyy'), 14000000155, '旅顺', '123456789012345160', to_date('06-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吴芳', 2, to_date('07-06-1970', 'dd-mm-yyyy'), 14000000156, '旅顺', '123456789012345161', to_date('07-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杨姲', 2, to_date('08-06-1970', 'dd-mm-yyyy'), 14000000157, '旅顺', '123456789012345162', to_date('08-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈湾', 2, to_date('09-06-1970', 'dd-mm-yyyy'), 14000000158, '旅顺', '123456789012345163', to_date('09-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冯姗', 2, to_date('10-06-1970', 'dd-mm-yyyy'), 14000000159, '旅顺', '123456789012345164', to_date('10-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑仪', 2, to_date('11-06-1970', 'dd-mm-yyyy'), 14000000160, '旅顺', '123456789012345165', to_date('11-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李呤', 2, to_date('12-06-1970', 'dd-mm-yyyy'), 14000000161, '旅顺', '123456789012345166', to_date('12-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李菁', 2, to_date('13-06-1970', 'dd-mm-yyyy'), 14000000162, '旅顺', '123456789012345167', to_date('13-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱音', 2, to_date('14-06-1970', 'dd-mm-yyyy'), 14000000163, '旅顺', '123456789012345168', to_date('14-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('刘茜', 2, to_date('15-06-1970', 'dd-mm-yyyy'), 14000000164, '旅顺', '123456789012345169', to_date('15-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑彤', 2, to_date('16-06-1970', 'dd-mm-yyyy'), 14000000165, '旅顺', '123456789012345170', to_date('16-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周雪', 2, to_date('17-06-1970', 'dd-mm-yyyy'), 14000000166, '旅顺', '123456789012345171', to_date('17-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('刘姳', 2, to_date('18-06-1970', 'dd-mm-yyyy'), 14000000167, '旅顺', '123456789012345172', to_date('18-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张琰', 2, to_date('19-06-1970', 'dd-mm-yyyy'), 14000000168, '旅顺', '123456789012345173', to_date('19-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杨苹', 2, to_date('20-06-1970', 'dd-mm-yyyy'), 14000000169, '旅顺', '123456789012345174', to_date('20-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈瓶', 2, to_date('21-06-1970', 'dd-mm-yyyy'), 14000000170, '旅顺', '123456789012345175', to_date('21-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吴丝', 2, to_date('22-06-1970', 'dd-mm-yyyy'), 14000000171, '旅顺', '123456789012345176', to_date('22-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵偲', 2, to_date('23-06-1970', 'dd-mm-yyyy'), 14000000172, '旅顺', '123456789012345177', to_date('23-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈渺', 2, to_date('24-06-1970', 'dd-mm-yyyy'), 14000000173, '旅顺', '123456789012345178', to_date('24-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郑瑛', 2, to_date('25-06-1970', 'dd-mm-yyyy'), 14000000174, '旅顺', '123456789012345179', to_date('25-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周滢', 2, to_date('26-06-1970', 'dd-mm-yyyy'), 14000000175, '旅顺', '123456789012345180', to_date('26-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈琴', 2, to_date('27-06-1970', 'dd-mm-yyyy'), 14000000176, '旅顺', '123456789012345181', to_date('27-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李育', 2, to_date('28-06-1970', 'dd-mm-yyyy'), 14000000177, '旅顺', '123456789012345182', to_date('28-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吴月', 2, to_date('29-06-1970', 'dd-mm-yyyy'), 14000000178, '旅顺', '123456789012345183', to_date('29-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李莉', 2, to_date('30-06-1970', 'dd-mm-yyyy'), 14000000179, '旅顺', '123456789012345184', to_date('30-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李芊', 2, to_date('01-07-1970', 'dd-mm-yyyy'), 14000000180, '旅顺', '123456789012345185', to_date('01-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李烟', 2, to_date('02-07-1970', 'dd-mm-yyyy'), 14000000181, '旅顺', '123456789012345186', to_date('02-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李香', 2, to_date('03-07-1970', 'dd-mm-yyyy'), 14000000182, '旅顺', '123456789012345187', to_date('03-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('刘嫦', 2, to_date('04-07-1970', 'dd-mm-yyyy'), 14000000183, '旅顺', '123456789012345188', to_date('04-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏昭', 2, to_date('05-07-1970', 'dd-mm-yyyy'), 14000000184, '旅顺', '123456789012345189', to_date('05-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('楚婕', 2, to_date('06-07-1970', 'dd-mm-yyyy'), 14000000185, '旅顺', '123456789012345190', to_date('06-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩卿', 2, to_date('07-07-1970', 'dd-mm-yyyy'), 14000000186, '旅顺', '123456789012345191', to_date('07-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周以柳', 1, to_date('13-09-2001', 'dd-mm-yyyy'), 14000000187, '旅顺', '123456789012355000', to_date('07-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('逢思娜', 1, to_date('11-05-2002', 'dd-mm-yyyy'), 14000000188, '旅顺', '123456789012355001', to_date('08-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('常惠心', 1, to_date('30-10-2001', 'dd-mm-yyyy'), 14000000189, '旅顺', '123456789012355002', to_date('09-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('向星星', 1, to_date('06-02-2002', 'dd-mm-yyyy'), 14000000190, '旅顺', '123456789012355003', to_date('10-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关西柠', 1, to_date('10-03-2002', 'dd-mm-yyyy'), 14000000191, '旅顺', '123456789012355004', to_date('11-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('丁静逸', 1, to_date('06-07-2001', 'dd-mm-yyyy'), 14000000192, '旅顺', '123456789012355005', to_date('12-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('汤迎梦', 1, to_date('11-04-2001', 'dd-mm-yyyy'), 14000000193, '旅顺', '123456789012355006', to_date('13-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('司韫玉', 1, to_date('14-06-2002', 'dd-mm-yyyy'), 14000000194, '旅顺', '123456789012355007', to_date('14-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('方惠娅', 1, to_date('21-10-2002', 'dd-mm-yyyy'), 14000000195, '旅顺', '123456789012355008', to_date('15-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('莘雍雅', 1, to_date('05-04-2002', 'dd-mm-yyyy'), 14000000196, '旅顺', '123456789012355009', to_date('16-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('浦依娜', 1, to_date('01-06-2002', 'dd-mm-yyyy'), 14000000197, '旅顺', '123456789012355010', to_date('17-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('连维娟', 1, to_date('21-01-2001', 'dd-mm-yyyy'), 14000000198, '旅顺', '123456789012355011', to_date('18-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杜乐心', 1, to_date('25-11-2002', 'dd-mm-yyyy'), 14000000199, '旅顺', '123456789012355012', to_date('19-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('糜斯琪', 1, to_date('24-05-2002', 'dd-mm-yyyy'), 14000000200, '旅顺', '123456789012355013', to_date('20-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('程夜白', 1, to_date('20-05-2001', 'dd-mm-yyyy'), 14000000201, '旅顺', '123456789012355014', to_date('21-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵秋彤', 1, to_date('22-06-2001', 'dd-mm-yyyy'), 14000000202, '旅顺', '123456789012355015', to_date('22-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阙野雪', 1, to_date('15-01-2001', 'dd-mm-yyyy'), 14000000203, '旅顺', '123456789012355016', to_date('23-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('堵映天', 1, to_date('25-04-2001', 'dd-mm-yyyy'), 14000000204, '旅顺', '123456789012355017', to_date('24-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('贺飞瑶', 1, to_date('22-10-2002', 'dd-mm-yyyy'), 14000000205, '旅顺', '123456789012355018', to_date('25-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('温妙可', 1, to_date('07-12-2002', 'dd-mm-yyyy'), 14000000206, '旅顺', '123456789012355019', to_date('26-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('方明熙', 1, to_date('19-12-2001', 'dd-mm-yyyy'), 14000000207, '旅顺', '123456789012355020', to_date('27-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钭雯婧', 1, to_date('09-04-2001', 'dd-mm-yyyy'), 14000000208, '旅顺', '123456789012355021', to_date('28-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韶雅安', 1, to_date('10-09-2001', 'dd-mm-yyyy'), 14000000209, '旅顺', '123456789012355022', to_date('29-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙萱彤', 1, to_date('15-11-2002', 'dd-mm-yyyy'), 14000000210, '旅顺', '123456789012355023', to_date('30-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('弓流如', 1, to_date('15-11-2002', 'dd-mm-yyyy'), 14000000211, '旅顺', '123456789012355024', to_date('31-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒋瑾萱', 1, to_date('29-01-2002', 'dd-mm-yyyy'), 14000000212, '旅顺', '123456789012355025', to_date('01-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('通璟雯', 1, to_date('18-06-2001', 'dd-mm-yyyy'), 14000000213, '旅顺', '123456789012355026', to_date('02-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宓慕蕊', 1, to_date('30-04-2001', 'dd-mm-yyyy'), 14000000214, '旅顺', '123456789012355027', to_date('03-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('董婉仪', 1, to_date('15-04-2001', 'dd-mm-yyyy'), 14000000215, '旅顺', '123456789012355028', to_date('04-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('文欣合', 1, to_date('10-12-2002', 'dd-mm-yyyy'), 14000000216, '旅顺', '123456789012355029', to_date('05-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('劳米琪', 1, to_date('20-04-2002', 'dd-mm-yyyy'), 14000000217, '旅顺', '123456789012355030', to_date('06-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('崔和平', 1, to_date('12-04-2001', 'dd-mm-yyyy'), 14000000218, '旅顺', '123456789012355031', to_date('07-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('高含香', 1, to_date('18-08-2002', 'dd-mm-yyyy'), 14000000219, '旅顺', '123456789012355032', to_date('08-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('卢玲羽', 1, to_date('13-12-2002', 'dd-mm-yyyy'), 14000000220, '旅顺', '123456789012355033', to_date('09-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('越友桃', 1, to_date('03-07-2001', 'dd-mm-yyyy'), 14000000221, '旅顺', '123456789012355034', to_date('10-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('饶辰雪', 1, to_date('13-07-2002', 'dd-mm-yyyy'), 14000000222, '旅顺', '123456789012355035', to_date('11-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('夏卓然', 1, to_date('15-06-2001', 'dd-mm-yyyy'), 14000000223, '旅顺', '123456789012355036', to_date('12-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吕晓绿', 1, to_date('07-11-2001', 'dd-mm-yyyy'), 14000000224, '旅顺', '123456789012355037', to_date('13-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈泽恩', 1, to_date('27-01-2002', 'dd-mm-yyyy'), 14000000225, '旅顺', '123456789012355038', to_date('14-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('仰翠琴', 1, to_date('06-09-2002', 'dd-mm-yyyy'), 14000000226, '旅顺', '123456789012355039', to_date('15-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阎梦桐', 1, to_date('25-02-2002', 'dd-mm-yyyy'), 14000000227, '旅顺', '123456789012355040', to_date('16-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蓬静秀', 1, to_date('08-07-2001', 'dd-mm-yyyy'), 14000000228, '旅顺', '123456789012355041', to_date('17-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吕飞荷', 1, to_date('30-08-2002', 'dd-mm-yyyy'), 14000000229, '旅顺', '123456789012355042', to_date('18-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('闻云梦', 1, to_date('14-11-2002', 'dd-mm-yyyy'), 14000000230, '旅顺', '123456789012355043', to_date('19-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('訾丝萝', 1, to_date('07-05-2001', 'dd-mm-yyyy'), 14000000231, '旅顺', '123456789012355044', to_date('20-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孟宜嘉', 1, to_date('27-10-2002', 'dd-mm-yyyy'), 14000000232, '旅顺', '123456789012355045', to_date('21-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('糜悦喜', 1, to_date('05-07-2001', 'dd-mm-yyyy'), 14000000233, '旅顺', '123456789012355046', to_date('22-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('菱孒凡', 1, to_date('22-02-2002', 'dd-mm-yyyy'), 14000000234, '旅顺', '123456789012355047', to_date('23-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('乌夏山', 1, to_date('26-11-2002', 'dd-mm-yyyy'), 14000000235, '旅顺', '123456789012355048', to_date('24-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吴芷兰', 1, to_date('17-07-2001', 'dd-mm-yyyy'), 14000000236, '旅顺', '123456789012355049', to_date('25-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('易绿柏', 1, to_date('26-01-2001', 'dd-mm-yyyy'), 14000000237, '旅顺', '123456789012355050', to_date('26-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郏雅楠', 1, to_date('14-01-2001', 'dd-mm-yyyy'), 14000000238, '旅顺', '123456789012355051', to_date('27-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('牧彩燕', 1, to_date('24-01-2001', 'dd-mm-yyyy'), 14000000239, '旅顺', '123456789012355052', to_date('28-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宰琳秀', 1, to_date('06-07-2002', 'dd-mm-yyyy'), 14000000240, '旅顺', '123456789012355053', to_date('29-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宫小瑜', 1, to_date('29-12-2001', 'dd-mm-yyyy'), 14000000241, '旅顺', '123456789012355054', to_date('30-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('莘慧秀', 1, to_date('29-01-2002', 'dd-mm-yyyy'), 14000000242, '旅顺', '123456789012355055', to_date('31-08-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('瞿晗蕊', 1, to_date('24-08-2001', 'dd-mm-yyyy'), 14000000243, '旅顺', '123456789012355056', to_date('01-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒯晓瑶', 1, to_date('22-12-2001', 'dd-mm-yyyy'), 14000000244, '旅顺', '123456789012355057', to_date('02-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('卢尤文', 1, to_date('31-08-2002', 'dd-mm-yyyy'), 14000000245, '旅顺', '123456789012355058', to_date('03-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('辛瑜文', 1, to_date('23-08-2002', 'dd-mm-yyyy'), 14000000246, '旅顺', '123456789012355059', to_date('04-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('薛颖馨', 1, to_date('08-10-2001', 'dd-mm-yyyy'), 14000000247, '旅顺', '123456789012355060', to_date('05-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周晓芬', 1, to_date('08-07-2002', 'dd-mm-yyyy'), 14000000248, '旅顺', '123456789012355061', to_date('06-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赖依玉', 1, to_date('16-06-2002', 'dd-mm-yyyy'), 14000000249, '旅顺', '123456789012355062', to_date('07-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('侯一凡', 1, to_date('11-06-2002', 'dd-mm-yyyy'), 14000000250, '旅顺', '123456789012355063', to_date('08-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('那新巧', 1, to_date('05-06-2002', 'dd-mm-yyyy'), 14000000251, '旅顺', '123456789012355064', to_date('09-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('石睿姿', 1, to_date('20-02-2001', 'dd-mm-yyyy'), 14000000252, '旅顺', '123456789012355065', to_date('10-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('刘三诗', 1, to_date('03-08-2002', 'dd-mm-yyyy'), 14000000253, '旅顺', '123456789012355066', to_date('11-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('武向彤', 1, to_date('17-04-2002', 'dd-mm-yyyy'), 14000000254, '旅顺', '123456789012355067', to_date('12-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郝痴灵', 1, to_date('07-02-2002', 'dd-mm-yyyy'), 14000000255, '旅顺', '123456789012355068', to_date('13-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('充以柳', 1, to_date('21-04-2001', 'dd-mm-yyyy'), 14000000256, '旅顺', '123456789012355069', to_date('14-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('夏雯琴', 1, to_date('30-03-2001', 'dd-mm-yyyy'), 14000000257, '旅顺', '123456789012355070', to_date('15-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('符许暖', 1, to_date('19-03-2002', 'dd-mm-yyyy'), 14000000258, '旅顺', '123456789012355071', to_date('16-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('瞿恬然', 1, to_date('13-08-2002', 'dd-mm-yyyy'), 14000000259, '旅顺', '123456789012355072', to_date('17-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('越芊芊', 1, to_date('28-08-2001', 'dd-mm-yyyy'), 14000000260, '旅顺', '123456789012355073', to_date('18-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('申莹莹', 1, to_date('07-07-2001', 'dd-mm-yyyy'), 14000000261, '旅顺', '123456789012355074', to_date('19-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('梁乐珍', 1, to_date('01-12-2002', 'dd-mm-yyyy'), 14000000262, '旅顺', '123456789012355075', to_date('20-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('许小凡', 1, to_date('17-08-2001', 'dd-mm-yyyy'), 14000000263, '旅顺', '123456789012355076', to_date('21-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('曾代玉', 1, to_date('24-11-2001', 'dd-mm-yyyy'), 14000000264, '旅顺', '123456789012355077', to_date('22-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('从慕悦', 1, to_date('17-11-2002', 'dd-mm-yyyy'), 14000000265, '旅顺', '123456789012355078', to_date('23-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('慎珺琦', 1, to_date('11-12-2001', 'dd-mm-yyyy'), 14000000266, '旅顺', '123456789012355079', to_date('24-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('辛虹雨', 1, to_date('28-10-2002', 'dd-mm-yyyy'), 14000000267, '旅顺', '123456789012355080', to_date('25-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('焦从露', 1, to_date('10-04-2001', 'dd-mm-yyyy'), 14000000268, '旅顺', '123456789012355081', to_date('26-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冷小凝', 1, to_date('19-10-2001', 'dd-mm-yyyy'), 14000000269, '旅顺', '123456789012355082', to_date('27-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('尹莺莺', 1, to_date('01-07-2002', 'dd-mm-yyyy'), 14000000270, '旅顺', '123456789012355083', to_date('28-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('卢夏璇', 1, to_date('20-11-2002', 'dd-mm-yyyy'), 14000000271, '旅顺', '123456789012355084', to_date('29-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒯尹夏', 1, to_date('26-04-2002', 'dd-mm-yyyy'), 14000000272, '旅顺', '123456789012355085', to_date('30-09-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宓秀颖', 1, to_date('13-12-2001', 'dd-mm-yyyy'), 14000000273, '旅顺', '123456789012355086', to_date('01-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('融璠瑜', 1, to_date('01-10-2001', 'dd-mm-yyyy'), 14000000274, '旅顺', '123456789012355087', to_date('02-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('逯书芹', 1, to_date('11-08-2002', 'dd-mm-yyyy'), 14000000275, '旅顺', '123456789012355088', to_date('03-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('罗平夏', 1, to_date('14-06-2002', 'dd-mm-yyyy'), 14000000276, '旅顺', '123456789012355089', to_date('04-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('司金枝', 1, to_date('10-02-2002', 'dd-mm-yyyy'), 14000000277, '旅顺', '123456789012355090', to_date('05-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒙富霞', 1, to_date('04-04-2001', 'dd-mm-yyyy'), 14000000278, '旅顺', '123456789012355091', to_date('06-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('惠石瑶', 1, to_date('28-08-2001', 'dd-mm-yyyy'), 14000000279, '旅顺', '123456789012355092', to_date('07-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('汤夜希', 1, to_date('28-09-2002', 'dd-mm-yyyy'), 14000000280, '旅顺', '123456789012355093', to_date('08-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('衡芳蕙', 1, to_date('19-07-2001', 'dd-mm-yyyy'), 14000000281, '旅顺', '123456789012355094', to_date('09-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('逢妙梦', 1, to_date('13-10-2001', 'dd-mm-yyyy'), 14000000282, '旅顺', '123456789012355095', to_date('10-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('仰思卉', 1, to_date('18-07-2001', 'dd-mm-yyyy'), 14000000283, '旅顺', '123456789012355096', to_date('11-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('劳婧文', 1, to_date('25-08-2002', 'dd-mm-yyyy'), 14000000284, '旅顺', '123456789012355097', to_date('12-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阴书雪', 1, to_date('18-01-2002', 'dd-mm-yyyy'), 14000000285, '旅顺', '123456789012355098', to_date('13-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('伊子珍', 1, to_date('10-08-2001', 'dd-mm-yyyy'), 14000000286, '旅顺', '123456789012355099', to_date('14-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('红赛玉', 1, to_date('17-05-2002', 'dd-mm-yyyy'), 14000000287, '旅顺', '123456789012355100', to_date('15-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('祖苏凌', 1, to_date('08-09-2001', 'dd-mm-yyyy'), 14000000288, '旅顺', '123456789012355101', to_date('16-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蓟曼凝', 1, to_date('17-07-2002', 'dd-mm-yyyy'), 14000000289, '旅顺', '123456789012355102', to_date('17-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郜韵梅', 1, to_date('08-03-2001', 'dd-mm-yyyy'), 14000000290, '旅顺', '123456789012355103', to_date('18-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('焦思琪', 1, to_date('03-04-2002', 'dd-mm-yyyy'), 14000000291, '旅顺', '123456789012355104', to_date('19-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('牧念梦', 1, to_date('11-03-2002', 'dd-mm-yyyy'), 14000000292, '旅顺', '123456789012355105', to_date('20-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蓟晶晶', 1, to_date('12-08-2001', 'dd-mm-yyyy'), 14000000293, '旅顺', '123456789012355106', to_date('21-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('叶婉容', 1, to_date('29-06-2002', 'dd-mm-yyyy'), 14000000294, '旅顺', '123456789012355107', to_date('22-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('家映萱', 1, to_date('22-06-2002', 'dd-mm-yyyy'), 14000000295, '旅顺', '123456789012355108', to_date('23-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('邵安卉', 1, to_date('10-09-2001', 'dd-mm-yyyy'), 14000000296, '旅顺', '123456789012355109', to_date('24-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('咸白容', 1, to_date('22-06-2002', 'dd-mm-yyyy'), 14000000297, '旅顺', '123456789012355110', to_date('25-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('咸怡畅', 1, to_date('24-11-2001', 'dd-mm-yyyy'), 14000000298, '旅顺', '123456789012355111', to_date('26-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沃浩然', 2, to_date('23-10-2001', 'dd-mm-yyyy'), 14000000299, '旅顺', '123456789012355112', to_date('27-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('汤飞尘', 2, to_date('27-01-2001', 'dd-mm-yyyy'), 14000000300, '旅顺', '123456789012355113', to_date('28-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('温同济', 2, to_date('12-07-2001', 'dd-mm-yyyy'), 14000000301, '旅顺', '123456789012355114', to_date('29-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('利修伟', 2, to_date('02-02-2002', 'dd-mm-yyyy'), 14000000302, '旅顺', '123456789012355115', to_date('30-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('戈宇荫', 2, to_date('09-03-2002', 'dd-mm-yyyy'), 14000000303, '旅顺', '123456789012355116', to_date('31-10-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('戴嘉荣', 2, to_date('31-08-2001', 'dd-mm-yyyy'), 14000000304, '旅顺', '123456789012355117', to_date('01-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('富阳德', 2, to_date('12-08-2001', 'dd-mm-yyyy'), 14000000305, '旅顺', '123456789012355118', to_date('02-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('步高峯', 2, to_date('01-12-2001', 'dd-mm-yyyy'), 14000000306, '旅顺', '123456789012355119', to_date('03-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('龙毅然', 2, to_date('08-06-2002', 'dd-mm-yyyy'), 14000000307, '旅顺', '123456789012355120', to_date('04-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('彭明德', 2, to_date('23-06-2001', 'dd-mm-yyyy'), 14000000308, '旅顺', '123456789012355121', to_date('05-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('闻凯唱', 2, to_date('21-01-2001', 'dd-mm-yyyy'), 14000000309, '旅顺', '123456789012355122', to_date('06-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陆俊爽', 2, to_date('14-03-2001', 'dd-mm-yyyy'), 14000000310, '旅顺', '123456789012355123', to_date('07-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('康景龙', 2, to_date('07-08-2002', 'dd-mm-yyyy'), 14000000311, '旅顺', '123456789012355124', to_date('08-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郭阳曜', 2, to_date('25-12-2001', 'dd-mm-yyyy'), 14000000312, '旅顺', '123456789012355125', to_date('09-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('籍永贞', 2, to_date('01-01-2001', 'dd-mm-yyyy'), 14000000313, '旅顺', '123456789012355126', to_date('10-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('益成济', 2, to_date('25-07-2002', 'dd-mm-yyyy'), 14000000314, '旅顺', '123456789012355127', to_date('11-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('谭俊达', 2, to_date('11-05-2002', 'dd-mm-yyyy'), 14000000315, '旅顺', '123456789012355128', to_date('12-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('温涵容', 2, to_date('29-09-2001', 'dd-mm-yyyy'), 14000000316, '旅顺', '123456789012355129', to_date('13-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关浩壤', 2, to_date('11-11-2001', 'dd-mm-yyyy'), 14000000317, '旅顺', '123456789012355130', to_date('14-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('寇锐志', 2, to_date('28-06-2001', 'dd-mm-yyyy'), 14000000318, '旅顺', '123456789012355131', to_date('15-11-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('从嘉瑞', 2, to_date('03-02-2002', 'dd-mm-yyyy'), 14000000530, '旅顺', '123456789012355343', to_date('15-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('甄理全', 2, to_date('28-02-2001', 'dd-mm-yyyy'), 14000000531, '旅顺', '123456789012355344', to_date('16-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('辛蕴藉', 2, to_date('21-05-2002', 'dd-mm-yyyy'), 14000000532, '旅顺', '123456789012355345', to_date('17-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('田成礼', 2, to_date('16-10-2001', 'dd-mm-yyyy'), 14000000533, '旅顺', '123456789012355346', to_date('18-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('袁弘济', 2, to_date('08-09-2001', 'dd-mm-yyyy'), 14000000534, '旅顺', '123456789012355347', to_date('19-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('庾弘文', 2, to_date('18-10-2001', 'dd-mm-yyyy'), 14000000535, '旅顺', '123456789012355348', to_date('20-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郜昊然', 2, to_date('07-06-2001', 'dd-mm-yyyy'), 14000000536, '旅顺', '123456789012355349', to_date('21-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('庾欣然', 2, to_date('06-07-2001', 'dd-mm-yyyy'), 14000000537, '旅顺', '123456789012355350', to_date('22-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('融乐池', 2, to_date('13-10-2002', 'dd-mm-yyyy'), 14000000538, '旅顺', '123456789012355351', to_date('23-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('卢敏才', 2, to_date('04-06-2001', 'dd-mm-yyyy'), 14000000539, '旅顺', '123456789012355352', to_date('24-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩博赡', 2, to_date('24-12-2001', 'dd-mm-yyyy'), 14000000540, '旅顺', '123456789012355353', to_date('25-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('毛天韵', 2, to_date('24-03-2002', 'dd-mm-yyyy'), 14000000541, '旅顺', '123456789012355354', to_date('26-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('曹阳旭', 2, to_date('20-05-2002', 'dd-mm-yyyy'), 14000000542, '旅顺', '123456789012355355', to_date('27-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郁鹏鲸', 2, to_date('23-05-2001', 'dd-mm-yyyy'), 14000000543, '旅顺', '123456789012355356', to_date('28-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('乌俊楚', 2, to_date('04-04-2002', 'dd-mm-yyyy'), 14000000544, '旅顺', '123456789012355357', to_date('29-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李永思', 2, to_date('20-06-2001', 'dd-mm-yyyy'), 14000000545, '旅顺', '123456789012355358', to_date('30-06-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('梁景焕', 2, to_date('05-07-2002', 'dd-mm-yyyy'), 14000000546, '旅顺', '123456789012355359', to_date('01-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('邰阳曦', 2, to_date('06-05-2002', 'dd-mm-yyyy'), 14000000547, '旅顺', '123456789012355360', to_date('02-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('江浩广', 2, to_date('29-01-2001', 'dd-mm-yyyy'), 14000000548, '旅顺', '123456789012355361', to_date('03-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('古博简', 2, to_date('21-02-2001', 'dd-mm-yyyy'), 14000000549, '旅顺', '123456789012355362', to_date('04-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宿恺歌', 2, to_date('01-08-2001', 'dd-mm-yyyy'), 14000000550, '旅顺', '123456789012355363', to_date('05-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郗斌蔚', 2, to_date('21-08-2002', 'dd-mm-yyyy'), 14000000551, '旅顺', '123456789012355364', to_date('06-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙鸿禧', 2, to_date('22-05-2001', 'dd-mm-yyyy'), 14000000552, '旅顺', '123456789012355365', to_date('07-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('辛弘致', 2, to_date('06-04-2001', 'dd-mm-yyyy'), 14000000553, '旅顺', '123456789012355366', to_date('08-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('越泰和', 2, to_date('23-09-2002', 'dd-mm-yyyy'), 14000000554, '旅顺', '123456789012355367', to_date('09-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('从浩博', 2, to_date('02-09-2001', 'dd-mm-yyyy'), 14000000555, '旅顺', '123456789012355368', to_date('10-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('逯明珠', 2, to_date('13-09-2001', 'dd-mm-yyyy'), 14000000556, '旅顺', '123456789012355369', to_date('11-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('司承宣', 2, to_date('20-07-2002', 'dd-mm-yyyy'), 14000000557, '旅顺', '123456789012355370', to_date('12-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('瞿经义', 2, to_date('03-01-2002', 'dd-mm-yyyy'), 14000000558, '旅顺', '123456789012355371', to_date('13-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('田鸿晖', 2, to_date('25-03-2001', 'dd-mm-yyyy'), 14000000559, '旅顺', '123456789012355372', to_date('14-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('乌高韵', 2, to_date('21-10-2002', 'dd-mm-yyyy'), 14000000560, '旅顺', '123456789012355373', to_date('15-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('傅嘉茂', 2, to_date('17-01-2001', 'dd-mm-yyyy'), 14000000561, '旅顺', '123456789012355374', to_date('16-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('龚阳夏', 2, to_date('24-02-2002', 'dd-mm-yyyy'), 14000000562, '旅顺', '123456789012355375', to_date('17-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('厉飞掣', 2, to_date('04-07-2002', 'dd-mm-yyyy'), 14000000563, '旅顺', '123456789012355376', to_date('18-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('熊鹤轩', 2, to_date('29-01-2001', 'dd-mm-yyyy'), 14000000564, '旅顺', '123456789012355377', to_date('19-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冉展鹏', 2, to_date('30-11-2002', 'dd-mm-yyyy'), 14000000565, '旅顺', '123456789012355378', to_date('20-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('金德元', 2, to_date('04-12-2002', 'dd-mm-yyyy'), 14000000566, '旅顺', '123456789012355379', to_date('21-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('何绍钧', 2, to_date('29-12-2002', 'dd-mm-yyyy'), 14000000567, '旅顺', '123456789012355380', to_date('22-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙良平', 2, to_date('12-01-2001', 'dd-mm-yyyy'), 14000000568, '旅顺', '123456789012355381', to_date('23-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('束弘毅', 2, to_date('25-10-2001', 'dd-mm-yyyy'), 14000000569, '旅顺', '123456789012355382', to_date('24-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('敖和泰', 2, to_date('30-04-2001', 'dd-mm-yyyy'), 14000000570, '旅顺', '123456789012355383', to_date('25-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('广经亘', 2, to_date('10-11-2001', 'dd-mm-yyyy'), 14000000571, '旅顺', '123456789012355384', to_date('26-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('邹茂彦', 2, to_date('23-05-2001', 'dd-mm-yyyy'), 14000000572, '旅顺', '123456789012355385', to_date('27-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吕文乐', 2, to_date('24-09-2002', 'dd-mm-yyyy'), 14000000573, '旅顺', '123456789012355386', to_date('28-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('刘玉书', 2, to_date('13-12-2002', 'dd-mm-yyyy'), 14000000574, '旅顺', '123456789012355387', to_date('29-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('越鸿福', 2, to_date('25-02-2002', 'dd-mm-yyyy'), 14000000575, '旅顺', '123456789012355388', to_date('30-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('须蕴和', 2, to_date('28-09-2002', 'dd-mm-yyyy'), 14000000576, '旅顺', '123456789012355389', to_date('31-07-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吕敏学', 2, to_date('14-05-2001', 'dd-mm-yyyy'), 14000000577, '旅顺', '123456789012355390', to_date('01-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吕光誉', 2, to_date('07-05-2001', 'dd-mm-yyyy'), 14000000578, '旅顺', '123456789012355391', to_date('02-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('焦乐人', 2, to_date('28-12-2002', 'dd-mm-yyyy'), 14000000579, '旅顺', '123456789012355392', to_date('03-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('农和悌', 2, to_date('26-05-2001', 'dd-mm-yyyy'), 14000000580, '旅顺', '123456789012355393', to_date('04-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒯琪睿', 2, to_date('21-06-2001', 'dd-mm-yyyy'), 14000000581, '旅顺', '123456789012355394', to_date('05-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('糜宏旷', 2, to_date('11-05-2002', 'dd-mm-yyyy'), 14000000582, '旅顺', '123456789012355395', to_date('06-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冀嘉佑', 2, to_date('07-06-2001', 'dd-mm-yyyy'), 14000000583, '旅顺', '123456789012355396', to_date('07-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('耿乐家', 2, to_date('24-09-2002', 'dd-mm-yyyy'), 14000000584, '旅顺', '123456789012355397', to_date('08-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('盖向阳', 2, to_date('04-02-2002', 'dd-mm-yyyy'), 14000000585, '旅顺', '123456789012355398', to_date('09-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈经国', 2, to_date('18-07-2001', 'dd-mm-yyyy'), 14000000586, '旅顺', '123456789012355399', to_date('10-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('傅奇正', 2, to_date('05-06-2001', 'dd-mm-yyyy'), 14000000587, '旅顺', '123456789012355400', to_date('11-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('梁浩穰', 2, to_date('29-01-2002', 'dd-mm-yyyy'), 14000000588, '旅顺', '123456789012355401', to_date('12-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('党兴腾', 2, to_date('19-03-2001', 'dd-mm-yyyy'), 14000000589, '旅顺', '123456789012355402', to_date('13-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('康鹏天', 2, to_date('01-01-2002', 'dd-mm-yyyy'), 14000000590, '旅顺', '123456789012355403', to_date('14-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('逢作人', 2, to_date('10-05-2002', 'dd-mm-yyyy'), 14000000591, '旅顺', '123456789012355404', to_date('15-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('万子平', 2, to_date('16-12-2002', 'dd-mm-yyyy'), 14000000592, '旅顺', '123456789012355405', to_date('16-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('崔成和', 2, to_date('21-10-2001', 'dd-mm-yyyy'), 14000000593, '旅顺', '123456789012355406', to_date('17-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('游建义', 2, to_date('01-10-2002', 'dd-mm-yyyy'), 14000000594, '旅顺', '123456789012355407', to_date('18-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈向荣', 2, to_date('28-05-2001', 'dd-mm-yyyy'), 14000000595, '旅顺', '123456789012355408', to_date('19-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李乐山', 2, to_date('27-08-2002', 'dd-mm-yyyy'), 14000000596, '旅顺', '123456789012355409', to_date('20-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('何斯伯', 2, to_date('21-02-2002', 'dd-mm-yyyy'), 14000000597, '旅顺', '123456789012355410', to_date('21-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('怀博涛', 2, to_date('25-01-2001', 'dd-mm-yyyy'), 14000000598, '旅顺', '123456789012355411', to_date('22-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('乔战', 2, to_date('30-12-2001', 'dd-mm-yyyy'), 14000000599, '旅顺', '123456789012355412', to_date('23-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张坚', 2, to_date('08-08-2002', 'dd-mm-yyyy'), 14000000600, '旅顺', '123456789012355413', to_date('24-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('寇佑', 2, to_date('10-12-2002', 'dd-mm-yyyy'), 14000000601, '旅顺', '123456789012355414', to_date('25-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('终丕', 2, to_date('11-06-2002', 'dd-mm-yyyy'), 14000000602, '旅顺', '123456789012355415', to_date('26-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('桓玫', 2, to_date('16-06-2002', 'dd-mm-yyyy'), 14000000603, '旅顺', '123456789012355416', to_date('27-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('巴僳', 2, to_date('01-06-2002', 'dd-mm-yyyy'), 14000000604, '旅顺', '123456789012355417', to_date('28-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('咸黎', 2, to_date('08-07-2002', 'dd-mm-yyyy'), 14000000605, '旅顺', '123456789012355418', to_date('29-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('红勇', 2, to_date('05-01-2002', 'dd-mm-yyyy'), 14000000606, '旅顺', '123456789012355419', to_date('30-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('束有', 2, to_date('10-05-2001', 'dd-mm-yyyy'), 14000000607, '旅顺', '123456789012355420', to_date('31-08-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('江村', 2, to_date('13-05-2002', 'dd-mm-yyyy'), 14000000608, '旅顺', '123456789012355421', to_date('01-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宋骢', 2, to_date('06-06-2001', 'dd-mm-yyyy'), 14000000609, '旅顺', '123456789012355422', to_date('02-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杨益', 2, to_date('25-03-2002', 'dd-mm-yyyy'), 14000000610, '旅顺', '123456789012355423', to_date('03-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('景祚', 2, to_date('02-02-2002', 'dd-mm-yyyy'), 14000000611, '旅顺', '123456789012355424', to_date('04-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('史纲', 2, to_date('30-06-2001', 'dd-mm-yyyy'), 14000000612, '旅顺', '123456789012355425', to_date('05-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('詹栋', 2, to_date('24-04-2001', 'dd-mm-yyyy'), 14000000613, '旅顺', '123456789012355426', to_date('06-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('利促', 2, to_date('25-12-2002', 'dd-mm-yyyy'), 14000000614, '旅顺', '123456789012355427', to_date('07-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('伊封', 2, to_date('23-02-2002', 'dd-mm-yyyy'), 14000000615, '旅顺', '123456789012355428', to_date('08-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关柴', 2, to_date('15-03-2002', 'dd-mm-yyyy'), 14000000616, '旅顺', '123456789012355429', to_date('09-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阙暠', 2, to_date('05-10-2001', 'dd-mm-yyyy'), 14000000617, '旅顺', '123456789012355430', to_date('10-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('鄂宾', 2, to_date('26-12-2002', 'dd-mm-yyyy'), 14000000618, '旅顺', '123456789012355431', to_date('11-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('金厚', 2, to_date('26-03-2002', 'dd-mm-yyyy'), 14000000619, '旅顺', '123456789012355432', to_date('12-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('祖伋', 2, to_date('27-09-2001', 'dd-mm-yyyy'), 14000000620, '旅顺', '123456789012355433', to_date('13-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('广诗', 2, to_date('03-05-2001', 'dd-mm-yyyy'), 14000000621, '旅顺', '123456789012355434', to_date('14-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('贾玄', 2, to_date('13-09-2002', 'dd-mm-yyyy'), 14000000622, '旅顺', '123456789012355435', to_date('15-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('曹邶', 2, to_date('03-09-2002', 'dd-mm-yyyy'), 14000000623, '旅顺', '123456789012355436', to_date('16-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('越昮', 2, to_date('20-07-2002', 'dd-mm-yyyy'), 14000000624, '旅顺', '123456789012355437', to_date('17-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('戈晷', 2, to_date('05-09-2001', 'dd-mm-yyyy'), 14000000625, '旅顺', '123456789012355438', to_date('18-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('寿汉', 2, to_date('01-11-2001', 'dd-mm-yyyy'), 14000000626, '旅顺', '123456789012355439', to_date('19-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('訾健', 2, to_date('24-03-2002', 'dd-mm-yyyy'), 14000000627, '旅顺', '123456789012355440', to_date('20-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('利玮', 2, to_date('20-02-2002', 'dd-mm-yyyy'), 14000000628, '旅顺', '123456789012355441', to_date('21-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('寇叔', 2, to_date('03-06-2001', 'dd-mm-yyyy'), 14000000629, '旅顺', '123456789012355442', to_date('22-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('鱼溢', 2, to_date('27-10-2001', 'dd-mm-yyyy'), 14000000630, '旅顺', '123456789012355443', to_date('23-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('范波', 2, to_date('04-01-2002', 'dd-mm-yyyy'), 14000000631, '旅顺', '123456789012355444', to_date('24-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('瞿河', 2, to_date('04-06-2002', 'dd-mm-yyyy'), 14000000632, '旅顺', '123456789012355445', to_date('25-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('慕才', 2, to_date('28-11-2001', 'dd-mm-yyyy'), 14000000633, '旅顺', '123456789012355446', to_date('26-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('茹嘉', 2, to_date('06-03-2002', 'dd-mm-yyyy'), 14000000634, '旅顺', '123456789012355447', to_date('27-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('勾裕', 2, to_date('28-10-2001', 'dd-mm-yyyy'), 14000000635, '旅顺', '123456789012355448', to_date('28-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陆轩', 2, to_date('10-10-2002', 'dd-mm-yyyy'), 14000000636, '旅顺', '123456789012355449', to_date('29-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关军', 2, to_date('28-08-2001', 'dd-mm-yyyy'), 14000000637, '旅顺', '123456789012355450', to_date('30-09-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙坤', 2, to_date('19-06-2001', 'dd-mm-yyyy'), 14000000638, '旅顺', '123456789012355451', to_date('01-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱鸿', 2, to_date('25-01-2002', 'dd-mm-yyyy'), 14000000639, '旅顺', '123456789012355452', to_date('02-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冉备', 2, to_date('15-04-2002', 'dd-mm-yyyy'), 14000000640, '旅顺', '123456789012355453', to_date('03-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('邹致', 2, to_date('21-04-2001', 'dd-mm-yyyy'), 14000000641, '旅顺', '123456789012355454', to_date('04-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('金浩', 2, to_date('11-05-2002', 'dd-mm-yyyy'), 14000000642, '旅顺', '123456789012355455', to_date('05-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('家耘', 2, to_date('20-12-2001', 'dd-mm-yyyy'), 14000000643, '旅顺', '123456789012355456', to_date('06-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('逯澉', 2, to_date('04-09-2002', 'dd-mm-yyyy'), 14000000644, '旅顺', '123456789012355457', to_date('07-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('夏庭', 2, to_date('29-03-2001', 'dd-mm-yyyy'), 14000000645, '旅顺', '123456789012355458', to_date('08-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('欧盈', 2, to_date('22-05-2002', 'dd-mm-yyyy'), 14000000646, '旅顺', '123456789012355459', to_date('09-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('史俊', 2, to_date('18-01-2002', 'dd-mm-yyyy'), 14000000647, '旅顺', '123456789012355460', to_date('10-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('弘绪', 2, to_date('22-10-2002', 'dd-mm-yyyy'), 14000000648, '旅顺', '123456789012355461', to_date('11-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('满葆', 2, to_date('01-08-2002', 'dd-mm-yyyy'), 14000000649, '旅顺', '123456789012355462', to_date('12-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('晏森', 2, to_date('27-10-2002', 'dd-mm-yyyy'), 14000000650, '旅顺', '123456789012355463', to_date('13-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('潘圣', 2, to_date('18-09-2002', 'dd-mm-yyyy'), 14000000651, '旅顺', '123456789012355464', to_date('14-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('刘僧', 2, to_date('13-09-2002', 'dd-mm-yyyy'), 14000000652, '旅顺', '123456789012355465', to_date('15-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('厍冠', 2, to_date('09-08-2001', 'dd-mm-yyyy'), 14000000653, '旅顺', '123456789012355466', to_date('16-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('糜卓', 2, to_date('21-10-2001', 'dd-mm-yyyy'), 14000000654, '旅顺', '123456789012355467', to_date('17-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('马密', 2, to_date('24-12-2002', 'dd-mm-yyyy'), 14000000655, '旅顺', '123456789012355468', to_date('18-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('璩寒', 2, to_date('22-08-2002', 'dd-mm-yyyy'), 14000000656, '旅顺', '123456789012355469', to_date('19-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宫佳', 2, to_date('12-09-2002', 'dd-mm-yyyy'), 14000000657, '旅顺', '123456789012355470', to_date('20-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙魁', 2, to_date('15-03-2001', 'dd-mm-yyyy'), 14000000658, '旅顺', '123456789012355471', to_date('21-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('惠灏', 2, to_date('25-07-2001', 'dd-mm-yyyy'), 14000000659, '旅顺', '123456789012355472', to_date('22-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蓬健', 2, to_date('25-11-2002', 'dd-mm-yyyy'), 14000000660, '旅顺', '123456789012355473', to_date('23-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('何峰', 2, to_date('11-10-2002', 'dd-mm-yyyy'), 14000000661, '旅顺', '123456789012355474', to_date('24-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('甘诤', 2, to_date('04-06-2001', 'dd-mm-yyyy'), 14000000662, '旅顺', '123456789012355475', to_date('25-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('戌佳', 2, to_date('22-05-2001', 'dd-mm-yyyy'), 14000000663, '旅顺', '123456789012355476', to_date('26-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('曹胜', 2, to_date('12-06-2001', 'dd-mm-yyyy'), 14000000664, '旅顺', '123456789012355477', to_date('27-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('漕璥', 2, to_date('05-03-2002', 'dd-mm-yyyy'), 14000000665, '旅顺', '123456789012355478', to_date('28-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('晃书', 2, to_date('23-08-2001', 'dd-mm-yyyy'), 14000000666, '旅顺', '123456789012355479', to_date('29-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('余琦', 2, to_date('14-10-2001', 'dd-mm-yyyy'), 14000000667, '旅顺', '123456789012355480', to_date('30-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('鄂诤', 2, to_date('13-03-2002', 'dd-mm-yyyy'), 14000000668, '旅顺', '123456789012355481', to_date('31-10-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('桂崇', 2, to_date('28-06-2001', 'dd-mm-yyyy'), 14000000669, '旅顺', '123456789012355482', to_date('01-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('桓清', 2, to_date('22-06-2002', 'dd-mm-yyyy'), 14000000670, '旅顺', '123456789012355483', to_date('02-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('茹祥', 2, to_date('04-11-2002', 'dd-mm-yyyy'), 14000000671, '旅顺', '123456789012355484', to_date('03-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('印厚', 2, to_date('01-05-2002', 'dd-mm-yyyy'), 14000000672, '旅顺', '123456789012355485', to_date('04-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('叶俟', 2, to_date('10-09-2002', 'dd-mm-yyyy'), 14000000673, '旅顺', '123456789012355486', to_date('05-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('雍江', 2, to_date('19-05-2001', 'dd-mm-yyyy'), 14000000674, '旅顺', '123456789012355487', to_date('06-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宓川', 2, to_date('07-07-2002', 'dd-mm-yyyy'), 14000000675, '旅顺', '123456789012355488', to_date('07-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('惠良', 2, to_date('07-12-2002', 'dd-mm-yyyy'), 14000000676, '旅顺', '123456789012355489', to_date('08-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('符列', 2, to_date('10-03-2002', 'dd-mm-yyyy'), 14000000677, '旅顺', '123456789012355490', to_date('09-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杜勋', 2, to_date('07-08-2001', 'dd-mm-yyyy'), 14000000678, '旅顺', '123456789012355491', to_date('10-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('瞿馗', 2, to_date('19-10-2002', 'dd-mm-yyyy'), 14000000679, '旅顺', '123456789012355492', to_date('11-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郜襦', 2, to_date('28-04-2001', 'dd-mm-yyyy'), 14000000680, '旅顺', '123456789012355493', to_date('12-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('咸宇', 2, to_date('19-12-2001', 'dd-mm-yyyy'), 14000000681, '旅顺', '123456789012355494', to_date('13-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('池鑫', 2, to_date('16-02-2001', 'dd-mm-yyyy'), 14000000682, '旅顺', '123456789012355495', to_date('14-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('家东', 2, to_date('09-12-2002', 'dd-mm-yyyy'), 14000000683, '旅顺', '123456789012355496', to_date('15-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('曾亮', 2, to_date('16-12-2002', 'dd-mm-yyyy'), 14000000684, '旅顺', '123456789012355497', to_date('16-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('须卓', 2, to_date('21-08-2002', 'dd-mm-yyyy'), 14000000685, '旅顺', '123456789012355498', to_date('17-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('从桓', 2, to_date('09-11-2002', 'dd-mm-yyyy'), 14000000686, '旅顺', '123456789012355499', to_date('18-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('芮劭', 2, to_date('07-12-2001', 'dd-mm-yyyy'), 14000000687, '旅顺', '123456789012355500', to_date('19-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒋俟', 2, to_date('15-09-2002', 'dd-mm-yyyy'), 14000000688, '旅顺', '123456789012355501', to_date('20-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阚殿', 2, to_date('29-06-2001', 'dd-mm-yyyy'), 14000000689, '旅顺', '123456789012355502', to_date('21-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('雍腾', 2, to_date('04-08-2001', 'dd-mm-yyyy'), 14000000690, '旅顺', '123456789012355503', to_date('22-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('农铖', 2, to_date('14-07-2002', 'dd-mm-yyyy'), 14000000691, '旅顺', '123456789012355504', to_date('23-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('符曹', 2, to_date('09-05-2002', 'dd-mm-yyyy'), 14000000692, '旅顺', '123456789012355505', to_date('24-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('马澔', 2, to_date('28-11-2001', 'dd-mm-yyyy'), 14000000693, '旅顺', '123456789012355506', to_date('25-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('姜弓', 2, to_date('24-02-2001', 'dd-mm-yyyy'), 14000000694, '旅顺', '123456789012355507', to_date('26-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('温墨', 2, to_date('05-09-2002', 'dd-mm-yyyy'), 14000000695, '旅顺', '123456789012355508', to_date('27-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('邹碫', 2, to_date('07-05-2002', 'dd-mm-yyyy'), 14000000696, '旅顺', '123456789012355509', to_date('28-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('庄谚', 2, to_date('20-04-2001', 'dd-mm-yyyy'), 14000000697, '旅顺', '123456789012355510', to_date('29-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('相僧', 2, to_date('02-11-2001', 'dd-mm-yyyy'), 14000000698, '旅顺', '123456789012355511', to_date('30-11-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('汤茗', 1, to_date('17-09-2002', 'dd-mm-yyyy'), 14000000699, '旅顺', '123456789012355512', to_date('01-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('邴澜', 1, to_date('18-07-2001', 'dd-mm-yyyy'), 14000000700, '旅顺', '123456789012355513', to_date('02-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('金波', 1, to_date('27-09-2002', 'dd-mm-yyyy'), 14000000701, '旅顺', '123456789012355514', to_date('03-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('菱惠', 1, to_date('30-04-2002', 'dd-mm-yyyy'), 14000000702, '旅顺', '123456789012355515', to_date('04-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('文霭', 1, to_date('09-03-2002', 'dd-mm-yyyy'), 14000000703, '旅顺', '123456789012355516', to_date('05-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('任夏', 1, to_date('16-06-2001', 'dd-mm-yyyy'), 14000000704, '旅顺', '123456789012355517', to_date('06-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('那玫', 1, to_date('01-07-2002', 'dd-mm-yyyy'), 14000000705, '旅顺', '123456789012355518', to_date('07-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('那淞', 1, to_date('01-01-2002', 'dd-mm-yyyy'), 14000000706, '旅顺', '123456789012355519', to_date('08-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('弘嫣', 1, to_date('07-01-2002', 'dd-mm-yyyy'), 14000000707, '旅顺', '123456789012355520', to_date('09-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郗春', 1, to_date('13-08-2002', 'dd-mm-yyyy'), 14000000708, '旅顺', '123456789012355521', to_date('10-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('古蓓', 1, to_date('12-05-2002', 'dd-mm-yyyy'), 14000000709, '旅顺', '123456789012355522', to_date('11-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵荔', 1, to_date('18-03-2002', 'dd-mm-yyyy'), 14000000710, '旅顺', '123456789012355523', to_date('12-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('国莹', 1, to_date('11-11-2001', 'dd-mm-yyyy'), 14000000711, '旅顺', '123456789012355524', to_date('13-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('罗姲', 1, to_date('30-03-2001', 'dd-mm-yyyy'), 14000000712, '旅顺', '123456789012355525', to_date('14-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('仰允', 1, to_date('27-03-2001', 'dd-mm-yyyy'), 14000000713, '旅顺', '123456789012355526', to_date('15-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('熊涵', 1, to_date('20-07-2002', 'dd-mm-yyyy'), 14000000714, '旅顺', '123456789012355527', to_date('16-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('范冉', 1, to_date('01-06-2001', 'dd-mm-yyyy'), 14000000715, '旅顺', '123456789012355528', to_date('17-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('唐蓝', 1, to_date('21-01-2002', 'dd-mm-yyyy'), 14000000716, '旅顺', '123456789012355529', to_date('18-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('耿君', 1, to_date('28-04-2001', 'dd-mm-yyyy'), 14000000717, '旅顺', '123456789012355530', to_date('19-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张姑', 1, to_date('17-07-2001', 'dd-mm-yyyy'), 14000000718, '旅顺', '123456789012355531', to_date('20-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('毛媚', 1, to_date('19-02-2001', 'dd-mm-yyyy'), 14000000719, '旅顺', '123456789012355532', to_date('21-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蔚姣', 1, to_date('18-07-2001', 'dd-mm-yyyy'), 14000000720, '旅顺', '123456789012355533', to_date('22-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('暨怜', 1, to_date('31-10-2002', 'dd-mm-yyyy'), 14000000721, '旅顺', '123456789012355534', to_date('23-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('易瑛', 1, to_date('29-06-2002', 'dd-mm-yyyy'), 14000000722, '旅顺', '123456789012355535', to_date('24-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('束枝', 1, to_date('05-05-2002', 'dd-mm-yyyy'), 14000000723, '旅顺', '123456789012355536', to_date('25-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('范炫', 1, to_date('11-03-2002', 'dd-mm-yyyy'), 14000000724, '旅顺', '123456789012355537', to_date('26-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('贡春', 1, to_date('17-04-2002', 'dd-mm-yyyy'), 14000000725, '旅顺', '123456789012355538', to_date('27-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('劳琼', 1, to_date('21-09-2001', 'dd-mm-yyyy'), 14000000726, '旅顺', '123456789012355539', to_date('28-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('利评', 1, to_date('19-04-2002', 'dd-mm-yyyy'), 14000000727, '旅顺', '123456789012355540', to_date('29-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('萧珴', 1, to_date('03-06-2001', 'dd-mm-yyyy'), 14000000728, '旅顺', '123456789012355541', to_date('30-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('姚允', 1, to_date('17-10-2002', 'dd-mm-yyyy'), 14000000729, '旅顺', '123456789012355542', to_date('31-12-2019', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('段影', 1, to_date('20-11-2001', 'dd-mm-yyyy'), 14000000730, '旅顺', '123456789012355543', to_date('01-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('茹梅', 1, to_date('11-11-2002', 'dd-mm-yyyy'), 14000000731, '旅顺', '123456789012355544', to_date('02-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('谭寒', 1, to_date('24-12-2002', 'dd-mm-yyyy'), 14000000732, '旅顺', '123456789012355545', to_date('03-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('桂珍', 1, to_date('29-08-2002', 'dd-mm-yyyy'), 14000000733, '旅顺', '123456789012355546', to_date('04-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('堵茜', 1, to_date('06-05-2001', 'dd-mm-yyyy'), 14000000734, '旅顺', '123456789012355547', to_date('05-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('彭瑞', 1, to_date('05-05-2001', 'dd-mm-yyyy'), 14000000735, '旅顺', '123456789012355548', to_date('06-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('金菁', 1, to_date('21-01-2002', 'dd-mm-yyyy'), 14000000736, '旅顺', '123456789012355549', to_date('07-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('通容', 1, to_date('18-05-2001', 'dd-mm-yyyy'), 14000000737, '旅顺', '123456789012355550', to_date('08-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('茹玫', 1, to_date('20-05-2001', 'dd-mm-yyyy'), 14000000738, '旅顺', '123456789012355551', to_date('09-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('养羽', 1, to_date('24-10-2001', 'dd-mm-yyyy'), 14000000739, '旅顺', '123456789012355552', to_date('10-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('曹琬', 1, to_date('03-07-2001', 'dd-mm-yyyy'), 14000000740, '旅顺', '123456789012355553', to_date('11-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('史音', 1, to_date('26-11-2002', 'dd-mm-yyyy'), 14000000741, '旅顺', '123456789012355554', to_date('12-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('曹蓝', 1, to_date('12-10-2001', 'dd-mm-yyyy'), 14000000742, '旅顺', '123456789012355555', to_date('13-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('辛茜', 1, to_date('13-05-2002', 'dd-mm-yyyy'), 14000000743, '旅顺', '123456789012355556', to_date('14-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('师霞', 1, to_date('10-02-2002', 'dd-mm-yyyy'), 14000000744, '旅顺', '123456789012355557', to_date('15-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙允', 1, to_date('16-10-2001', 'dd-mm-yyyy'), 14000000745, '旅顺', '123456789012355558', to_date('16-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('曾婧', 1, to_date('02-04-2002', 'dd-mm-yyyy'), 14000000746, '旅顺', '123456789012355559', to_date('17-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('暴漩', 1, to_date('03-05-2002', 'dd-mm-yyyy'), 14000000747, '旅顺', '123456789012355560', to_date('18-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('姜黛', 1, to_date('04-12-2001', 'dd-mm-yyyy'), 14000000748, '旅顺', '123456789012355561', to_date('19-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郏希', 1, to_date('09-08-2001', 'dd-mm-yyyy'), 14000000749, '旅顺', '123456789012355562', to_date('20-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('索翠', 1, to_date('08-08-2002', 'dd-mm-yyyy'), 14000000750, '旅顺', '123456789012355563', to_date('21-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('廖绛', 1, to_date('02-05-2002', 'dd-mm-yyyy'), 14000000751, '旅顺', '123456789012355564', to_date('22-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蔡素', 1, to_date('05-08-2001', 'dd-mm-yyyy'), 14000000752, '旅顺', '123456789012355565', to_date('23-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒙澜', 1, to_date('18-02-2001', 'dd-mm-yyyy'), 14000000753, '旅顺', '123456789012355566', to_date('24-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('司姑', 1, to_date('29-04-2002', 'dd-mm-yyyy'), 14000000754, '旅顺', '123456789012355567', to_date('25-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('卓汇', 1, to_date('13-01-2001', 'dd-mm-yyyy'), 14000000755, '旅顺', '123456789012355568', to_date('26-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒙悦', 1, to_date('01-04-2002', 'dd-mm-yyyy'), 14000000756, '旅顺', '123456789012355569', to_date('27-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('江平', 1, to_date('07-09-2002', 'dd-mm-yyyy'), 14000000757, '旅顺', '123456789012355570', to_date('28-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('牛玟', 1, to_date('11-07-2002', 'dd-mm-yyyy'), 14000000758, '旅顺', '123456789012355571', to_date('29-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('松蓓', 1, to_date('22-03-2002', 'dd-mm-yyyy'), 14000000759, '旅顺', '123456789012355572', to_date('30-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('连渺', 1, to_date('26-11-2001', 'dd-mm-yyyy'), 14000000760, '旅顺', '123456789012355573', to_date('31-01-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('须明', 1, to_date('10-02-2002', 'dd-mm-yyyy'), 14000000761, '旅顺', '123456789012355574', to_date('01-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('扶华', 1, to_date('30-03-2001', 'dd-mm-yyyy'), 14000000762, '旅顺', '123456789012355575', to_date('02-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('万竹', 1, to_date('28-01-2001', 'dd-mm-yyyy'), 14000000763, '旅顺', '123456789012355576', to_date('03-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('扈颜', 1, to_date('28-04-2001', 'dd-mm-yyyy'), 14000000764, '旅顺', '123456789012355577', to_date('04-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('雍曼', 1, to_date('27-05-2001', 'dd-mm-yyyy'), 14000000765, '旅顺', '123456789012355578', to_date('05-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('莘莎', 1, to_date('10-02-2002', 'dd-mm-yyyy'), 14000000766, '旅顺', '123456789012355579', to_date('06-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('叶芯', 1, to_date('21-07-2001', 'dd-mm-yyyy'), 14000000767, '旅顺', '123456789012355580', to_date('07-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('王婉', 1, to_date('13-06-2001', 'dd-mm-yyyy'), 14000000768, '旅顺', '123456789012355581', to_date('08-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱喜', 1, to_date('19-09-2002', 'dd-mm-yyyy'), 14000000769, '旅顺', '123456789012355582', to_date('09-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('相婧', 1, to_date('24-02-2001', 'dd-mm-yyyy'), 14000000770, '旅顺', '123456789012355583', to_date('10-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('闻伊', 1, to_date('08-06-2002', 'dd-mm-yyyy'), 14000000771, '旅顺', '123456789012355584', to_date('11-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蓬珆', 1, to_date('29-03-2001', 'dd-mm-yyyy'), 14000000772, '旅顺', '123456789012355585', to_date('12-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('林香', 1, to_date('26-09-2002', 'dd-mm-yyyy'), 14000000773, '旅顺', '123456789012355586', to_date('13-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('潘渺', 1, to_date('14-06-2002', 'dd-mm-yyyy'), 14000000774, '旅顺', '123456789012355587', to_date('14-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('许娉', 1, to_date('02-06-2002', 'dd-mm-yyyy'), 14000000775, '旅顺', '123456789012355588', to_date('15-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('从颜', 1, to_date('14-12-2001', 'dd-mm-yyyy'), 14000000776, '旅顺', '123456789012355589', to_date('16-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('权珠', 1, to_date('28-07-2001', 'dd-mm-yyyy'), 14000000777, '旅顺', '123456789012355590', to_date('17-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('翟珆', 1, to_date('15-05-2002', 'dd-mm-yyyy'), 14000000778, '旅顺', '123456789012355591', to_date('18-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('毋枝', 1, to_date('13-02-2001', 'dd-mm-yyyy'), 14000000779, '旅顺', '123456789012355592', to_date('19-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('扶育', 1, to_date('03-03-2001', 'dd-mm-yyyy'), 14000000780, '旅顺', '123456789012355593', to_date('20-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('丁琬', 1, to_date('15-06-2001', 'dd-mm-yyyy'), 14000000781, '旅顺', '123456789012355594', to_date('21-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('訾馡', 1, to_date('15-01-2001', 'dd-mm-yyyy'), 14000000782, '旅顺', '123456789012355595', to_date('22-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('璩育', 1, to_date('03-10-2002', 'dd-mm-yyyy'), 14000000783, '旅顺', '123456789012355596', to_date('23-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('红蕾', 1, to_date('17-06-2002', 'dd-mm-yyyy'), 14000000784, '旅顺', '123456789012355597', to_date('24-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('贺昭', 1, to_date('15-11-2001', 'dd-mm-yyyy'), 14000000785, '旅顺', '123456789012355598', to_date('25-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('夏媱', 1, to_date('10-02-2001', 'dd-mm-yyyy'), 14000000786, '旅顺', '123456789012355599', to_date('26-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('景雪', 1, to_date('26-01-2001', 'dd-mm-yyyy'), 14000000787, '旅顺', '123456789012355600', to_date('27-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('广嫱', 1, to_date('21-08-2001', 'dd-mm-yyyy'), 14000000788, '旅顺', '123456789012355601', to_date('28-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩缨', 1, to_date('28-03-2002', 'dd-mm-yyyy'), 14000000789, '旅顺', '123456789012355602', to_date('29-02-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('任英', 1, to_date('12-06-2002', 'dd-mm-yyyy'), 14000000790, '旅顺', '123456789012355603', to_date('01-03-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('融冷', 1, to_date('08-03-2001', 'dd-mm-yyyy'), 14000000791, '旅顺', '123456789012355604', to_date('02-03-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('熊云', 1, to_date('27-02-2002', 'dd-mm-yyyy'), 14000000792, '旅顺', '123456789012355605', to_date('03-03-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宁绣', 1, to_date('31-12-2001', 'dd-mm-yyyy'), 14000000793, '旅顺', '123456789012355606', to_date('04-03-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阴芮', 1, to_date('13-05-2002', 'dd-mm-yyyy'), 14000000794, '旅顺', '123456789012355607', to_date('05-03-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蓟霜', 1, to_date('14-07-2002', 'dd-mm-yyyy'), 14000000795, '旅顺', '123456789012355608', to_date('06-03-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('乜姳', 1, to_date('15-01-2002', 'dd-mm-yyyy'), 14000000796, '旅顺', '123456789012355609', to_date('07-03-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('张煜', 1, to_date('09-10-2001', 'dd-mm-yyyy'), 14000000797, '旅顺', '123456789012355610', to_date('08-03-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('储莉', 1, to_date('26-05-2002', 'dd-mm-yyyy'), 14000000798, '旅顺', '123456789012355611', to_date('09-03-2020', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('邴路英', 1, to_date('01-01-1970', 'dd-mm-yyyy'), 13999999999, '旅顺', '123456789012355612', to_date('01-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('杨惠美', 1, to_date('02-01-1970', 'dd-mm-yyyy'), 14000000000, '漳平', '123456789012355613', to_date('02-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('璩许洌', 1, to_date('03-01-1970', 'dd-mm-yyyy'), 14000000001, '福安', '123456789012355614', to_date('03-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('连冬莲', 1, to_date('04-01-1970', 'dd-mm-yyyy'), 14000000002, '福鼎', '123456789012355615', to_date('04-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宋晓彤', 1, to_date('05-01-1970', 'dd-mm-yyyy'), 14000000003, '兰州', '123456789012355616', to_date('05-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('桓韵诗', 1, to_date('06-01-1970', 'dd-mm-yyyy'), 14000000004, '嘉峪关', '123456789012355617', to_date('06-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('寇白梦', 1, to_date('07-01-1970', 'dd-mm-yyyy'), 14000000005, '金昌', '123456789012355618', to_date('07-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('陈平晓', 1, to_date('08-01-1970', 'dd-mm-yyyy'), 14000000006, '白银', '123456789012355619', to_date('08-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('龙妙音', 1, to_date('09-01-1970', 'dd-mm-yyyy'), 14000000007, '天水', '123456789012355620', to_date('09-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('姚婷婷', 1, to_date('10-01-1970', 'dd-mm-yyyy'), 14000000008, '酒泉', '123456789012355621', to_date('10-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('司银柳', 1, to_date('11-01-1970', 'dd-mm-yyyy'), 14000000009, '张掖', '123456789012355622', to_date('11-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('巴梓颖', 1, to_date('12-01-1970', 'dd-mm-yyyy'), 14000000010, '武威', '123456789012355623', to_date('12-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('古秋彤', 1, to_date('13-01-1970', 'dd-mm-yyyy'), 14000000011, '庆阳', '123456789012355624', to_date('13-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('方娜兰', 1, to_date('14-01-1970', 'dd-mm-yyyy'), 14000000012, '平凉', '123456789012355625', to_date('14-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郭雅晗', 1, to_date('15-01-1970', 'dd-mm-yyyy'), 14000000013, '定西', '123456789012355626', to_date('15-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('公芳蕙', 1, to_date('16-01-1970', 'dd-mm-yyyy'), 14000000014, '陇南', '123456789012355627', to_date('16-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('辛希恩', 1, to_date('17-01-1970', 'dd-mm-yyyy'), 14000000015, '玉门', '123456789012355628', to_date('17-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孟艳玲', 1, to_date('18-01-1970', 'dd-mm-yyyy'), 14000000016, '敦煌', '123456789012355629', to_date('18-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('扶绪婷', 1, to_date('19-01-1970', 'dd-mm-yyyy'), 14000000017, '临夏', '123456789012355630', to_date('19-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('容安筠', 1, to_date('20-01-1970', 'dd-mm-yyyy'), 14000000018, '合作', '123456789012355631', to_date('20-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('温灵卉', 1, to_date('21-01-1970', 'dd-mm-yyyy'), 14000000019, '级城市', '123456789012355632', to_date('21-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('古娅楠', 1, to_date('22-01-1970', 'dd-mm-yyyy'), 14000000020, '级城市', '123456789012355633', to_date('22-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('彭雁荷', 1, to_date('23-01-1970', 'dd-mm-yyyy'), 14000000021, '清远', '123456789012355634', to_date('23-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('越清淑', 1, to_date('24-01-1970', 'dd-mm-yyyy'), 14000000022, '韶关', '123456789012355635', to_date('24-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('空梓涵', 1, to_date('25-01-1970', 'dd-mm-yyyy'), 14000000023, '河源', '123456789012355636', to_date('25-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('黄冰萍', 1, to_date('26-01-1970', 'dd-mm-yyyy'), 14000000024, '梅州', '123456789012355637', to_date('26-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('籍天菱', 1, to_date('27-01-1970', 'dd-mm-yyyy'), 14000000025, '潮州', '123456789012355638', to_date('27-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('梁雅山', 1, to_date('28-01-1970', 'dd-mm-yyyy'), 14000000026, '汕头', '123456789012355639', to_date('28-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('符宛曼', 1, to_date('29-01-1970', 'dd-mm-yyyy'), 14000000027, '揭阳', '123456789012355640', to_date('29-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('连华月', 1, to_date('30-01-1970', 'dd-mm-yyyy'), 14000000028, '汕尾', '123456789012355641', to_date('30-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('牛书兰', 1, to_date('31-01-1970', 'dd-mm-yyyy'), 14000000029, '惠州', '123456789012355642', to_date('31-01-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('梁小雯', 1, to_date('01-02-1970', 'dd-mm-yyyy'), 14000000030, '东莞', '123456789012355643', to_date('01-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('莘迎松', 1, to_date('02-02-1970', 'dd-mm-yyyy'), 14000000031, '珠海', '123456789012355644', to_date('02-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('暨安然', 1, to_date('03-02-1970', 'dd-mm-yyyy'), 14000000032, '中山', '123456789012355645', to_date('03-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('何夏初', 1, to_date('04-02-1970', 'dd-mm-yyyy'), 14000000033, '江门', '123456789012355646', to_date('04-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('龙静美', 1, to_date('05-02-1970', 'dd-mm-yyyy'), 14000000034, '佛山', '123456789012355647', to_date('05-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('乔馨兰', 1, to_date('06-02-1970', 'dd-mm-yyyy'), 14000000035, '肇庆', '123456789012355648', to_date('06-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('贡云英', 1, to_date('07-02-1970', 'dd-mm-yyyy'), 14000000036, '云浮', '123456789012355649', to_date('07-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈尹夏', 1, to_date('08-02-1970', 'dd-mm-yyyy'), 14000000037, '阳江', '123456789012355650', to_date('08-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('韩静枫', 1, to_date('09-02-1970', 'dd-mm-yyyy'), 14000000038, '茂名', '123456789012355651', to_date('09-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('党瑛蔓', 1, to_date('10-02-1970', 'dd-mm-yyyy'), 14000000039, '湛江', '123456789012355652', to_date('10-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('符从云', 1, to_date('11-02-1970', 'dd-mm-yyyy'), 14000000040, '从化', '123456789012355653', to_date('11-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('璩水绿', 1, to_date('12-02-1970', 'dd-mm-yyyy'), 14000000041, '增城', '123456789012355654', to_date('12-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('潘芷茹', 1, to_date('13-02-1970', 'dd-mm-yyyy'), 14000000042, '英德', '123456789012355655', to_date('13-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孟念蕾', 1, to_date('14-02-1970', 'dd-mm-yyyy'), 14000000043, '连州', '123456789012355656', to_date('14-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('顾兰芝', 1, to_date('15-02-1970', 'dd-mm-yyyy'), 14000000044, '乐昌', '123456789012355657', to_date('15-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒲真洁', 1, to_date('16-02-1970', 'dd-mm-yyyy'), 14000000045, '南雄', '123456789012355658', to_date('16-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宁忆翠', 1, to_date('17-02-1970', 'dd-mm-yyyy'), 14000000046, '兴宁', '123456789012355659', to_date('17-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('桂怡悦', 1, to_date('18-02-1970', 'dd-mm-yyyy'), 14000000047, '普宁', '123456789012355660', to_date('18-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('殳慕青', 1, to_date('19-02-1970', 'dd-mm-yyyy'), 14000000048, '陆丰', '123456789012355661', to_date('19-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('益令慧', 1, to_date('20-02-1970', 'dd-mm-yyyy'), 14000000049, '恩平', '123456789012355662', to_date('20-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('金绮怀', 1, to_date('21-02-1970', 'dd-mm-yyyy'), 14000000050, '台山', '123456789012355663', to_date('21-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('燕倚云', 1, to_date('22-02-1970', 'dd-mm-yyyy'), 14000000051, '开平', '123456789012355664', to_date('22-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('漕安阳', 1, to_date('23-02-1970', 'dd-mm-yyyy'), 14000000052, '鹤山', '123456789012355665', to_date('23-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('祖如心', 1, to_date('24-02-1970', 'dd-mm-yyyy'), 14000000053, '高要', '123456789012355666', to_date('24-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('关若英', 1, to_date('25-02-1970', 'dd-mm-yyyy'), 14000000054, '四会', '123456789012355667', to_date('25-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('菱博丽', 1, to_date('26-02-1970', 'dd-mm-yyyy'), 14000000055, '罗定', '123456789012355668', to_date('26-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周贝丽', 1, to_date('27-02-1970', 'dd-mm-yyyy'), 14000000056, '阳春', '123456789012355669', to_date('27-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('夏夜午', 1, to_date('28-02-1970', 'dd-mm-yyyy'), 14000000057, '化州', '123456789012355670', to_date('28-02-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吴绿蕊', 1, to_date('01-03-1970', 'dd-mm-yyyy'), 14000000058, '信宜', '123456789012355671', to_date('01-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('唐子琳', 1, to_date('02-03-1970', 'dd-mm-yyyy'), 14000000059, '高州', '123456789012355672', to_date('02-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('相钊莹', 1, to_date('03-03-1970', 'dd-mm-yyyy'), 14000000060, '吴川', '123456789012355673', to_date('03-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('高雨双', 1, to_date('04-03-1970', 'dd-mm-yyyy'), 14000000061, '廉江', '123456789012355674', to_date('04-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('暨宇芳', 1, to_date('05-03-1970', 'dd-mm-yyyy'), 14000000062, '雷州', '123456789012355675', to_date('05-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赵叶帆', 1, to_date('06-03-1970', 'dd-mm-yyyy'), 14000000063, '贵阳', '123456789012355676', to_date('06-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('厉珠佩', 1, to_date('07-03-1970', 'dd-mm-yyyy'), 14000000064, '六盘水', '123456789012355677', to_date('07-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('鱼雅静', 1, to_date('08-03-1970', 'dd-mm-yyyy'), 14000000065, '遵义', '123456789012355678', to_date('08-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('劳暄婷', 1, to_date('09-03-1970', 'dd-mm-yyyy'), 14000000066, '安顺', '123456789012355679', to_date('09-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宿流丽', 1, to_date('10-03-1970', 'dd-mm-yyyy'), 14000000067, '毕节', '123456789012355680', to_date('10-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('养谷菱', 1, to_date('11-03-1970', 'dd-mm-yyyy'), 14000000068, '铜仁', '123456789012355681', to_date('11-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郁苏幻', 1, to_date('12-03-1970', 'dd-mm-yyyy'), 14000000069, '清镇', '123456789012355682', to_date('12-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('谷琪华', 1, to_date('13-03-1970', 'dd-mm-yyyy'), 14000000070, '赤水', '123456789012355683', to_date('13-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('通惜文', 1, to_date('14-03-1970', 'dd-mm-yyyy'), 14000000071, '仁怀', '123456789012355684', to_date('14-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('班南晴', 1, to_date('15-03-1970', 'dd-mm-yyyy'), 14000000072, '凯里', '123456789012355685', to_date('15-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蓟山彤', 1, to_date('16-03-1970', 'dd-mm-yyyy'), 14000000073, '都匀', '123456789012355686', to_date('16-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阚冷雪', 1, to_date('17-03-1970', 'dd-mm-yyyy'), 14000000074, '兴义', '123456789012355687', to_date('17-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈滢滢', 1, to_date('18-03-1970', 'dd-mm-yyyy'), 14000000075, '福泉', '123456789012355688', to_date('18-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('红忆远', 1, to_date('19-03-1970', 'dd-mm-yyyy'), 14000000076, '石家庄', '123456789012355689', to_date('19-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孙平卉', 1, to_date('20-03-1970', 'dd-mm-yyyy'), 14000000077, '邯郸', '123456789012355690', to_date('20-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宁平和', 1, to_date('21-03-1970', 'dd-mm-yyyy'), 14000000078, '唐山', '123456789012355691', to_date('21-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('劳筱雪', 1, to_date('22-03-1970', 'dd-mm-yyyy'), 14000000079, '保定', '123456789012355692', to_date('22-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郭冬云', 1, to_date('23-03-1970', 'dd-mm-yyyy'), 14000000080, '秦皇岛', '123456789012355693', to_date('23-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孔洋洋', 1, to_date('24-03-1970', 'dd-mm-yyyy'), 14000000081, '邢台', '123456789012355694', to_date('24-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吕鸾瑶', 1, to_date('25-03-1970', 'dd-mm-yyyy'), 14000000082, '张家口', '123456789012355695', to_date('25-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('宁艳芳', 1, to_date('26-03-1970', 'dd-mm-yyyy'), 14000000083, '承德', '123456789012355696', to_date('26-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('马玟玉', 1, to_date('27-03-1970', 'dd-mm-yyyy'), 14000000084, '沧州', '123456789012355697', to_date('27-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('尹曜儿', 1, to_date('28-03-1970', 'dd-mm-yyyy'), 14000000085, '廊坊', '123456789012355698', to_date('28-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('敖痴灵', 1, to_date('29-03-1970', 'dd-mm-yyyy'), 14000000086, '衡水', '123456789012355699', to_date('29-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('班婉燕', 1, to_date('30-03-1970', 'dd-mm-yyyy'), 14000000087, '辛集', '123456789012355700', to_date('30-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('于诗筠', 1, to_date('31-03-1970', 'dd-mm-yyyy'), 14000000088, '藁城', '123456789012355701', to_date('31-03-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阚典雅', 1, to_date('01-04-1970', 'dd-mm-yyyy'), 14000000089, '晋州', '123456789012355702', to_date('01-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('潘苏荷', 1, to_date('02-04-1970', 'dd-mm-yyyy'), 14000000090, '新乐', '123456789012355703', to_date('02-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('糜高洁', 1, to_date('03-04-1970', 'dd-mm-yyyy'), 14000000091, '鹿泉', '123456789012355704', to_date('03-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钟曼安', 1, to_date('04-04-1970', 'dd-mm-yyyy'), 14000000092, '遵化', '123456789012355705', to_date('04-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阙诗蕊', 1, to_date('05-04-1970', 'dd-mm-yyyy'), 14000000093, '迁安', '123456789012355706', to_date('05-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('瞿虹玉', 1, to_date('06-04-1970', 'dd-mm-yyyy'), 14000000094, '霸州', '123456789012355707', to_date('06-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒋寄灵', 1, to_date('07-04-1970', 'dd-mm-yyyy'), 14000000095, '三河', '123456789012355708', to_date('07-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('璩仙韵', 1, to_date('08-04-1970', 'dd-mm-yyyy'), 14000000096, '定州', '123456789012355709', to_date('08-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('高娟秀', 1, to_date('09-04-1970', 'dd-mm-yyyy'), 14000000097, '涿州', '123456789012355710', to_date('09-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阎静美', 1, to_date('10-04-1970', 'dd-mm-yyyy'), 14000000098, '安国', '123456789012355711', to_date('10-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('空宇丞', 1, to_date('11-04-1970', 'dd-mm-yyyy'), 14000000099, '高碑店', '123456789012355712', to_date('11-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('赖沂秀', 1, to_date('12-04-1970', 'dd-mm-yyyy'), 14000000100, '泊头', '123456789012355713', to_date('12-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('逯叶芳', 1, to_date('13-04-1970', 'dd-mm-yyyy'), 14000000101, '任丘', '123456789012355714', to_date('13-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('扶岚翠', 1, to_date('14-04-1970', 'dd-mm-yyyy'), 14000000102, '黄骅', '123456789012355715', to_date('14-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('汪蕊珠', 1, to_date('15-04-1970', 'dd-mm-yyyy'), 14000000103, '河间', '123456789012355716', to_date('15-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冀婧玟', 1, to_date('16-04-1970', 'dd-mm-yyyy'), 14000000104, '冀州', '123456789012355717', to_date('16-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('双寒凡', 1, to_date('17-04-1970', 'dd-mm-yyyy'), 14000000105, '深州', '123456789012355718', to_date('17-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('汤丹萱', 1, to_date('18-04-1970', 'dd-mm-yyyy'), 14000000106, '南宫', '123456789012355719', to_date('18-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('贺笑翠', 1, to_date('19-04-1970', 'dd-mm-yyyy'), 14000000107, '沙河', '123456789012355720', to_date('19-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('苍翠琴', 1, to_date('20-04-1970', 'dd-mm-yyyy'), 14000000108, '武安', '123456789012355721', to_date('20-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('劳诗茹', 1, to_date('21-04-1970', 'dd-mm-yyyy'), 14000000109, '级城市', '123456789012355722', to_date('21-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('寇诗兰', 1, to_date('22-04-1970', 'dd-mm-yyyy'), 14000000110, '齐齐哈尔', '123456789012355723', to_date('22-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('益阿柒', 1, to_date('23-04-1970', 'dd-mm-yyyy'), 14000000111, '黑河', '123456789012355724', to_date('23-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('慕莉颖', 1, to_date('24-04-1970', 'dd-mm-yyyy'), 14000000112, '大庆', '123456789012355725', to_date('24-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('许初雪', 1, to_date('25-04-1970', 'dd-mm-yyyy'), 14000000113, '伊春', '123456789012355726', to_date('25-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('居凝芙', 1, to_date('26-04-1970', 'dd-mm-yyyy'), 14000000114, '鹤岗', '123456789012355727', to_date('26-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('吕念烟', 1, to_date('27-04-1970', 'dd-mm-yyyy'), 14000000115, '佳木斯', '123456789012355728', to_date('27-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('魏泯熙', 1, to_date('28-04-1970', 'dd-mm-yyyy'), 14000000116, '双鸭山', '123456789012355729', to_date('28-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('郭凌翠', 1, to_date('29-04-1970', 'dd-mm-yyyy'), 14000000117, '七台河', '123456789012355730', to_date('29-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('王逸云', 1, to_date('30-04-1970', 'dd-mm-yyyy'), 14000000118, '鸡西', '123456789012355731', to_date('30-04-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒙小霞', 1, to_date('01-05-1970', 'dd-mm-yyyy'), 14000000119, '牡丹江', '123456789012355732', to_date('01-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('龙安琪', 1, to_date('02-05-1970', 'dd-mm-yyyy'), 14000000120, '绥化', '123456789012355733', to_date('02-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('阴宫莹', 1, to_date('03-05-1970', 'dd-mm-yyyy'), 14000000121, '双城', '123456789012355734', to_date('03-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('牧长丽', 1, to_date('04-05-1970', 'dd-mm-yyyy'), 14000000122, '尚志', '123456789012355735', to_date('04-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('公忆秋', 1, to_date('05-05-1970', 'dd-mm-yyyy'), 14000000123, '五常', '123456789012355736', to_date('05-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('常幻丝', 1, to_date('06-05-1970', 'dd-mm-yyyy'), 14000000124, '阿城', '123456789012355737', to_date('06-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('朱雨寒', 1, to_date('07-05-1970', 'dd-mm-yyyy'), 14000000125, '讷河', '123456789012355738', to_date('07-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蔚小玉', 1, to_date('08-05-1970', 'dd-mm-yyyy'), 14000000126, '北安', '123456789012355739', to_date('08-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('沈子珍', 1, to_date('09-05-1970', 'dd-mm-yyyy'), 14000000127, '五大连池', '123456789012355740', to_date('09-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('周思宸', 1, to_date('10-05-1970', 'dd-mm-yyyy'), 14000000128, '铁力', '123456789012355741', to_date('10-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('巢悠馨', 1, to_date('11-05-1970', 'dd-mm-yyyy'), 14000000129, '同江', '123456789012355742', to_date('11-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('方之双', 1, to_date('12-05-1970', 'dd-mm-yyyy'), 14000000130, '富锦', '123456789012355743', to_date('12-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('李灵溪', 1, to_date('13-05-1970', 'dd-mm-yyyy'), 14000000131, '虎林', '123456789012355744', to_date('13-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('濮薏冉', 1, to_date('14-05-1970', 'dd-mm-yyyy'), 14000000132, '密山', '123456789012355745', to_date('14-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('徐安静', 1, to_date('15-05-1970', 'dd-mm-yyyy'), 14000000133, '绥芬河', '123456789012355746', to_date('15-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('乌雅辰', 1, to_date('16-05-1970', 'dd-mm-yyyy'), 14000000134, '海林', '123456789012355747', to_date('16-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('晏白安', 1, to_date('17-05-1970', 'dd-mm-yyyy'), 14000000135, '宁安', '123456789012355748', to_date('17-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('冀姝丽', 1, to_date('18-05-1970', 'dd-mm-yyyy'), 14000000136, '安达', '123456789012355749', to_date('18-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('那琳爰', 1, to_date('19-05-1970', 'dd-mm-yyyy'), 14000000137, '肇东', '123456789012355750', to_date('19-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('崔若云', 1, to_date('20-05-1970', 'dd-mm-yyyy'), 14000000138, '海伦', '123456789012355751', to_date('20-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱伟娜', 1, to_date('21-05-1970', 'dd-mm-yyyy'), 14000000139, '郑州', '123456789012355752', to_date('21-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('武殷漓', 1, to_date('22-05-1970', 'dd-mm-yyyy'), 14000000140, '开封', '123456789012355753', to_date('22-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('朱端敏', 1, to_date('23-05-1970', 'dd-mm-yyyy'), 14000000141, '洛阳', '123456789012355754', to_date('23-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('浦凌瑶', 1, to_date('24-05-1970', 'dd-mm-yyyy'), 14000000142, '平顶山', '123456789012355755', to_date('24-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('仰傲晴', 1, to_date('25-05-1970', 'dd-mm-yyyy'), 14000000143, '安阳', '123456789012355756', to_date('25-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('徐炜琳', 1, to_date('26-05-1970', 'dd-mm-yyyy'), 14000000144, '鹤壁', '123456789012355757', to_date('26-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('贾书翠', 1, to_date('27-05-1970', 'dd-mm-yyyy'), 14000000145, '新乡', '123456789012355758', to_date('27-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('靳小珍', 1, to_date('28-05-1970', 'dd-mm-yyyy'), 14000000146, '焦作', '123456789012355759', to_date('28-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('盖朗宁', 1, to_date('29-05-1970', 'dd-mm-yyyy'), 14000000147, '濮阳', '123456789012355760', to_date('29-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('蒲尤文', 1, to_date('30-05-1970', 'dd-mm-yyyy'), 14000000148, '许昌', '123456789012355761', to_date('30-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('余碧灵', 1, to_date('31-05-1970', 'dd-mm-yyyy'), 14000000149, '漯河', '123456789012355762', to_date('31-05-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('林琼英', 1, to_date('01-06-1970', 'dd-mm-yyyy'), 14000000150, '三门峡', '123456789012355763', to_date('01-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('贾辰蓉', 1, to_date('02-06-1970', 'dd-mm-yyyy'), 14000000151, '南阳', '123456789012355764', to_date('02-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('邰灵竹', 1, to_date('03-06-1970', 'dd-mm-yyyy'), 14000000152, '商丘', '123456789012355765', to_date('03-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('曹依心', 1, to_date('04-06-1970', 'dd-mm-yyyy'), 14000000153, '周口', '123456789012355766', to_date('04-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('史昕妍', 1, to_date('05-06-1970', 'dd-mm-yyyy'), 14000000154, '驻马店', '123456789012355767', to_date('05-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('尹童童', 1, to_date('06-06-1970', 'dd-mm-yyyy'), 14000000155, '旅顺', '123456789012355768', to_date('06-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('尚慧英', 1, to_date('07-06-1970', 'dd-mm-yyyy'), 14000000156, '旅顺', '123456789012355769', to_date('07-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('庄玲玉', 1, to_date('08-06-1970', 'dd-mm-yyyy'), 14000000157, '旅顺', '123456789012355770', to_date('08-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('后叶嘉', 1, to_date('09-06-1970', 'dd-mm-yyyy'), 14000000158, '旅顺', '123456789012355771', to_date('09-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('訾珠佩', 1, to_date('10-06-1970', 'dd-mm-yyyy'), 14000000159, '旅顺', '123456789012355772', to_date('10-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('侯展文', 1, to_date('11-06-1970', 'dd-mm-yyyy'), 14000000160, '旅顺', '123456789012355773', to_date('11-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('益宵月', 1, to_date('12-06-1970', 'dd-mm-yyyy'), 14000000161, '旅顺', '123456789012355774', to_date('12-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('苏冷珍', 1, to_date('13-06-1970', 'dd-mm-yyyy'), 14000000162, '旅顺', '123456789012355775', to_date('13-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('通洁玉', 1, to_date('14-06-1970', 'dd-mm-yyyy'), 14000000163, '旅顺', '123456789012355776', to_date('14-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('习布衣', 1, to_date('15-06-1970', 'dd-mm-yyyy'), 14000000164, '旅顺', '123456789012355777', to_date('15-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('侯书芹', 1, to_date('16-06-1970', 'dd-mm-yyyy'), 14000000165, '旅顺', '123456789012355778', to_date('16-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('能依童', 1, to_date('17-06-1970', 'dd-mm-yyyy'), 14000000166, '旅顺', '123456789012355779', to_date('17-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('养松月', 1, to_date('18-06-1970', 'dd-mm-yyyy'), 14000000167, '旅顺', '123456789012355780', to_date('18-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('晏蓉洁', 1, to_date('19-06-1970', 'dd-mm-yyyy'), 14000000168, '旅顺', '123456789012355781', to_date('19-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('古雅美', 1, to_date('20-06-1970', 'dd-mm-yyyy'), 14000000169, '旅顺', '123456789012355782', to_date('20-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('温音华', 1, to_date('21-06-1970', 'dd-mm-yyyy'), 14000000170, '旅顺', '123456789012355783', to_date('21-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('易曹文', 1, to_date('22-06-1970', 'dd-mm-yyyy'), 14000000171, '旅顺', '123456789012355784', to_date('22-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('桓尔风', 1, to_date('23-06-1970', 'dd-mm-yyyy'), 14000000172, '旅顺', '123456789012355785', to_date('23-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('钱依童', 1, to_date('24-06-1970', 'dd-mm-yyyy'), 14000000173, '旅顺', '123456789012355786', to_date('24-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('罗沛凝', 1, to_date('25-06-1970', 'dd-mm-yyyy'), 14000000174, '旅顺', '123456789012355787', to_date('25-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('孟芳馥', 1, to_date('26-06-1970', 'dd-mm-yyyy'), 14000000175, '旅顺', '123456789012355788', to_date('26-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('龚宵月', 1, to_date('27-06-1970', 'dd-mm-yyyy'), 14000000176, '旅顺', '123456789012355789', to_date('27-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('屠婧宁', 1, to_date('28-06-1970', 'dd-mm-yyyy'), 14000000177, '旅顺', '123456789012355790', to_date('28-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('汲青丝', 1, to_date('29-06-1970', 'dd-mm-yyyy'), 14000000178, '旅顺', '123456789012355791', to_date('29-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('慕千凡', 1, to_date('30-06-1970', 'dd-mm-yyyy'), 14000000179, '旅顺', '123456789012355792', to_date('30-06-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('后沐葵', 1, to_date('01-07-1970', 'dd-mm-yyyy'), 14000000180, '旅顺', '123456789012355793', to_date('01-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('满馨兰', 1, to_date('02-07-1970', 'dd-mm-yyyy'), 14000000181, '旅顺', '123456789012355794', to_date('02-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('卢晓星', 1, to_date('03-07-1970', 'dd-mm-yyyy'), 14000000182, '旅顺', '123456789012355795', to_date('03-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('闻洁雅', 1, to_date('04-07-1970', 'dd-mm-yyyy'), 14000000183, '旅顺', '123456789012355796', to_date('04-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('符秋莲', 1, to_date('05-07-1970', 'dd-mm-yyyy'), 14000000184, '旅顺', '123456789012355797', to_date('05-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('羿雪冰', 1, to_date('06-07-1970', 'dd-mm-yyyy'), 14000000185, '旅顺', '123456789012355798', to_date('06-07-2018', 'dd-mm-yyyy'));

insert into people (NAME, SEX, BIRTHDAY, CONTACT, ADDRESS, CARD_ID, JOIN_DATE)
values ('卓燕妮', 1, to_date('07-07-1970', 'dd-mm-yyyy'), 14000000186, '旅顺', '123456789012355799', to_date('07-07-2018', 'dd-mm-yyyy'));


```

## teacher

```
insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345005', '070814', 5194.00, 1, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345006', '070815', 4286.00, 2, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345007', '070816', 7972.00, 3, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345008', '070817', 4910.00, 4, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345009', '070818', 6796.00, 5, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345010', '070819', 11158.00, 6, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345011', '070820', 8343.00, 7, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345012', '070821', 3083.00, 8, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345013', '070822', 5213.00, 9, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345014', '070823', 9497.00, 10, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345015', '070824', 7965.00, 11, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345016', '070825', 8285.00, 12, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345017', '070826', 4206.00, 13, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345018', '070827', 6971.00, 14, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345019', '070828', 6313.00, 15, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345020', '070829', 4460.00, 16, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345021', '070830', 6871.00, 17, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345022', '070831', 3092.00, 18, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345023', '070832', 5448.00, 19, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345024', '070833', 3215.00, 20, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345025', '070834', 8058.00, 21, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345026', '070835', 5203.00, 22, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345027', '070836', 11442.00, 23, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345028', '070837', 11143.00, 24, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345029', '070838', 4267.00, 25, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345030', '070839', 6788.00, 26, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345031', '070840', 4462.00, 27, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345032', '070841', 10426.00, 28, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345033', '070842', 7852.00, 29, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345034', '070843', 11588.00, 30, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345035', '070844', 5752.00, 31, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345036', '070845', 8844.00, 32, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345037', '070846', 5497.00, 33, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345038', '070847', 6900.00, 34, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345039', '070848', 4298.00, 35, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345040', '070849', 8173.00, 36, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345041', '070850', 9650.00, 37, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345042', '070851', 3622.00, 38, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345043', '070852', 8776.00, 39, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345044', '070853', 8357.00, 40, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345045', '070854', 4768.00, 41, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345046', '070855', 9931.00, 42, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345047', '070856', 5369.00, 43, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345048', '070857', 7465.00, 44, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345049', '070858', 8616.00, 45, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345050', '070859', 6827.00, 46, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345051', '070860', 3716.00, 47, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345052', '070861', 11567.00, 48, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345053', '070862', 9419.00, 49, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345054', '070863', 10396.00, 50, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345055', '070864', 6934.00, 51, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345056', '070865', 3184.00, 52, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345057', '070866', 4792.00, 53, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345058', '070867', 11084.00, 54, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345059', '070868', 7715.00, 1, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345060', '070869', 7071.00, 2, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345061', '070870', 10742.00, 3, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345062', '070871', 6106.00, 4, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345063', '070872', 4998.00, 5, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345064', '070873', 5394.00, 6, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345065', '070874', 11014.00, 7, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345066', '070875', 11407.00, 8, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345067', '070876', 10580.00, 9, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345068', '070877', 5851.00, 10, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345069', '070878', 5630.00, 11, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345070', '070879', 8462.00, 12, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345071', '070880', 11936.00, 13, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345072', '070881', 10866.00, 14, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345073', '070882', 4327.00, 15, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345074', '070883', 4111.00, 16, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345075', '070884', 4821.00, 17, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345076', '070885', 10862.00, 18, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345077', '070886', 3677.00, 19, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345078', '070887', 8994.00, 20, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345079', '070888', 6436.00, 21, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345080', '070889', 3300.00, 22, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345081', '070890', 6333.00, 23, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345082', '070891', 7341.00, 24, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345083', '070892', 7219.00, 25, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345084', '070893', 4059.00, 26, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345085', '070894', 6735.00, 27, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345086', '070895', 6503.00, 28, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345087', '070896', 3229.00, 29, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345088', '070897', 3513.00, 30, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345089', '070898', 6212.00, 31, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345090', '070899', 9853.00, 32, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345091', '070900', 9363.00, 33, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345092', '070901', 10935.00, 34, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345093', '070902', 8932.00, 35, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345094', '070903', 11478.00, 36, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345095', '070904', 9034.00, 37, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345096', '070905', 10642.00, 38, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345097', '070906', 11508.00, 39, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345098', '070907', 5059.00, 40, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345099', '070908', 11222.00, 41, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345100', '070909', 10322.00, 42, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345101', '070910', 6436.00, 43, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345102', '070911', 8686.00, 44, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345103', '070912', 3463.00, 45, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345104', '070913', 10556.00, 46, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345105', '070914', 4927.00, 47, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345106', '070915', 11560.00, 48, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345107', '070916', 3035.00, 49, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345108', '070917', 9666.00, 50, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345109', '070918', 7736.00, 51, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345110', '070919', 8064.00, 52, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345111', '070920', 7602.00, 53, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345112', '070921', 4825.00, 54, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345113', '070922', 11617.00, 1, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345114', '070923', 8355.00, 2, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345115', '070924', 8698.00, 3, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345116', '070925', 4800.00, 4, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345117', '070926', 8831.00, 5, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345118', '070927', 3104.00, 6, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345119', '070928', 9185.00, 7, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345120', '070929', 5584.00, 8, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345121', '070930', 11856.00, 9, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345122', '070931', 9480.00, 10, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345123', '070932', 10337.00, 11, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345124', '070933', 3461.00, 12, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345125', '070934', 11663.00, 13, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345126', '070935', 6676.00, 14, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345127', '070936', 10872.00, 15, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345128', '070937', 3904.00, 16, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345129', '070938', 8067.00, 17, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345130', '070939', 7904.00, 18, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345131', '070940', 4121.00, 19, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345132', '070941', 11073.00, 20, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345133', '070942', 7266.00, 21, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345134', '070943', 6139.00, 22, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345135', '070944', 9385.00, 23, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345136', '070945', 7833.00, 24, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345137', '070946', 5929.00, 25, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345138', '070947', 8250.00, 26, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345139', '070948', 4472.00, 27, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345140', '070949', 4132.00, 28, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345141', '070950', 11681.00, 29, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345142', '070951', 9390.00, 30, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345143', '070952', 6206.00, 31, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345144', '070953', 9117.00, 32, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345145', '070954', 9168.00, 33, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345146', '070955', 7577.00, 34, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345147', '070956', 10736.00, 35, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345148', '070957', 4514.00, 36, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345149', '070958', 4396.00, 37, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345150', '070959', 10359.00, 38, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345151', '070960', 11554.00, 39, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345152', '070961', 5884.00, 40, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345153', '070962', 4001.00, 41, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345154', '070963', 10334.00, 42, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345155', '070964', 11174.00, 43, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345156', '070965', 11243.00, 44, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345157', '070966', 8474.00, 45, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345158', '070967', 11587.00, 46, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345159', '070968', 8170.00, 47, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345160', '070969', 11260.00, 48, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345161', '070970', 11681.00, 49, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345162', '070971', 10247.00, 50, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345163', '070972', 3507.00, 51, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345164', '070973', 3006.00, 52, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345165', '070974', 5504.00, 53, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);

insert into teachers (CARD_ID, JOB_ID, SALARY, COURSE_ID, CREATE_DATE, DELETE_DATE)
values ('123456789012345166', '070975', 8483.00, 54, to_date('03-08-2023 13:32:05', 'dd-mm-yyyy hh24:mi:ss'), null);
```
