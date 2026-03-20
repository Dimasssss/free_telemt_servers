# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```
Этот сервер пользуется большим спросом. Я арендовал еще один такой же, чтобы распределить нагрузку.

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-20 08:59:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 56525.1 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1280210
telemt_connections_bad_total 69423
telemt_connections_current 1841
telemt_connections_me_current 1841
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 33405
telemt_upstream_connect_attempt_total 10851
telemt_upstream_connect_success_total 10737
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 10851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 6879
telemt_me_reconnect_success_total 6826
telemt_me_reader_eof_total 7223
telemt_me_idle_close_by_peer_total 7221
telemt_me_route_drop_no_conn_total 378177
telemt_me_route_drop_channel_closed_total 201
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1055601
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5380
telemt_desync_full_logged_total 1930
telemt_desync_suppressed_total 3450
telemt_desync_frames_bucket_total{bucket="1_2"} 1116
telemt_desync_frames_bucket_total{bucket="3_10"} 2083
telemt_desync_frames_bucket_total{bucket="gt_10"} 2181
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 102
telemt_me_writer_removed_unexpected_total 6899
telemt_me_writer_restored_same_endpoint_total 6813
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 455
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1055149
telemt_user_connections_current{user="hello"} 1841
telemt_user_octets_from_client{user="hello"} 39249334648 (36.55 GB)
telemt_user_octets_to_client{user="hello"} 357473468297 (332.92 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 632
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 72980.6 (20h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5437751
telemt_connections_bad_total 481282
telemt_connections_current 4179
telemt_connections_me_current 4179
telemt_handshake_timeouts_total 113758
telemt_upstream_connect_attempt_total 13421
telemt_upstream_connect_success_total 13132
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 13421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12569
telemt_me_reconnect_success_total 8288
telemt_me_reader_eof_total 8868
telemt_me_idle_close_by_peer_total 8867
telemt_me_route_drop_no_conn_total 3245266
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4481572
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16620
telemt_desync_full_logged_total 5550
telemt_desync_suppressed_total 11070
telemt_desync_frames_bucket_total{bucket="1_2"} 3302
telemt_desync_frames_bucket_total{bucket="3_10"} 6491
telemt_desync_frames_bucket_total{bucket="gt_10"} 6827
telemt_pool_swap_total 64
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 117
telemt_me_writer_removed_unexpected_total 8540
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 8233
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 4483770
telemt_user_connections_current{user="hello"} 4179
telemt_user_octets_from_client{user="hello"} 61121573026 (56.92 GB)
telemt_user_octets_to_client{user="hello"} 1501362637938 (1.37 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1449
telemt_user_unique_ips_recent_window{user="hello"} 569
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 6322.4 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365346
telemt_connections_bad_total 28957
telemt_connections_current 2838
telemt_connections_me_current 2838
telemt_handshake_timeouts_total 4191
telemt_upstream_connect_attempt_total 1273
telemt_upstream_connect_success_total 1273
telemt_upstream_connect_attempts_per_request{bucket="1"} 1273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 892
telemt_me_reconnect_success_total 880
telemt_me_reader_eof_total 864
telemt_me_idle_close_by_peer_total 864
telemt_me_route_drop_no_conn_total 124462
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300709
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1382
telemt_desync_full_logged_total 465
telemt_desync_suppressed_total 917
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 472
telemt_desync_frames_bucket_total{bucket="gt_10"} 649
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 868
telemt_me_writer_restored_same_endpoint_total 880
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 300938
telemt_user_connections_current{user="hello"} 2838
telemt_user_octets_from_client{user="hello"} 5045127784 (4.70 GB)
telemt_user_octets_to_client{user="hello"} 120168962479 (111.92 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 1089
telemt_user_unique_ips_recent_window{user="hello"} 426
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 72958.9 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4938700
telemt_connections_bad_total 597512
telemt_connections_current 5559
telemt_connections_me_current 5559
telemt_handshake_timeouts_total 72524
telemt_upstream_connect_attempt_total 13098
telemt_upstream_connect_success_total 12988
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 13098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5990
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3102
telemt_me_reconnect_attempts_total 8862
telemt_me_reconnect_success_total 7893
telemt_me_reader_eof_total 8270
telemt_me_idle_close_by_peer_total 8265
telemt_me_route_drop_no_conn_total 3026480
telemt_me_route_drop_channel_closed_total 306
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3570969
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12393
telemt_desync_full_logged_total 3960
telemt_desync_suppressed_total 8433
telemt_desync_frames_bucket_total{bucket="1_2"} 2910
telemt_desync_frames_bucket_total{bucket="3_10"} 4657
telemt_desync_frames_bucket_total{bucket="gt_10"} 4826
telemt_pool_swap_total 72
telemt_me_writer_close_signal_drop_total 365
telemt_me_writer_removed_unexpected_total 8000
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7892
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 3577330
telemt_user_connections_current{user="hello"} 5559
telemt_user_octets_from_client{user="hello"} 54467973574 (50.73 GB)
telemt_user_octets_to_client{user="hello"} 1335531093736 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1750
telemt_user_unique_ips_recent_window{user="hello"} 720
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 72946.6 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6697897
telemt_connections_bad_total 321920
telemt_connections_current 5392
telemt_connections_me_current 5392
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 90454
telemt_upstream_connect_attempt_total 83027
telemt_upstream_connect_success_total 71267
telemt_upstream_connect_fail_total 11760
telemt_upstream_connect_attempts_per_request{bucket="1"} 83027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11760
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 11423
telemt_me_reconnect_success_total 8283
telemt_me_reader_eof_total 8636
telemt_me_idle_close_by_peer_total 8634
telemt_me_route_drop_no_conn_total 9783731
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5764314
telemt_me_writer_pick_total{mode="p2c",result="full"} 4273
telemt_me_writer_pick_total{mode="p2c",result="closed"} 804
telemt_me_writer_pick_blocking_fallback_total 5052
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14831
telemt_desync_full_logged_total 4286
telemt_desync_suppressed_total 10545
telemt_desync_frames_bucket_total{bucket="1_2"} 3312
telemt_desync_frames_bucket_total{bucket="3_10"} 5938
telemt_desync_frames_bucket_total{bucket="gt_10"} 5581
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 835
telemt_me_writer_removed_unexpected_total 9129
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 8279
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 846
telemt_user_connections_total{user="hello"} 5823759
telemt_user_connections_current{user="hello"} 5392
telemt_user_octets_from_client{user="hello"} 53212596867 (49.56 GB)
telemt_user_octets_to_client{user="hello"} 921842140345 (858.53 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1596
telemt_user_unique_ips_recent_window{user="hello"} 930
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 10529.4 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2292951
telemt_connections_bad_total 163191
telemt_connections_current 5783
telemt_connections_me_current 5783
telemt_handshake_timeouts_total 27370
telemt_upstream_connect_attempt_total 1797
telemt_upstream_connect_success_total 1785
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 1230
telemt_me_reconnect_success_total 1227
telemt_me_reader_eof_total 1254
telemt_me_idle_close_by_peer_total 1253
telemt_me_route_drop_no_conn_total 3586064
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1957329
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4094
telemt_desync_full_logged_total 1192
telemt_desync_suppressed_total 2902
telemt_desync_frames_bucket_total{bucket="1_2"} 768
telemt_desync_frames_bucket_total{bucket="3_10"} 1675
telemt_desync_frames_bucket_total{bucket="gt_10"} 1651
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 1232
telemt_me_writer_restored_same_endpoint_total 1197
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1952136
telemt_user_connections_current{user="hello"} 5783
telemt_user_octets_from_client{user="hello"} 16896436820 (15.74 GB)
telemt_user_octets_to_client{user="hello"} 251389037948 (234.12 GB)
telemt_user_unique_ips_current{user="hello"} 1879
telemt_user_unique_ips_recent_window{user="hello"} 774
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 106.5 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5038
telemt_connections_bad_total 174
telemt_connections_current 654
telemt_connections_me_current 654
telemt_relay_adaptive_promotions_total 2
telemt_relay_adaptive_hard_promotions_total 2
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 1520
telemt_upstream_connect_success_total 1518
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 80
telemt_me_reconnect_success_total 78
telemt_me_route_drop_no_conn_total 896
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3135
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 6
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_close_signal_drop_total 17
telemt_me_writer_removed_unexpected_total 17
telemt_me_writer_restored_same_endpoint_total 76
telemt_me_writer_restored_fallback_total 2
telemt_me_no_writer_failfast_total 168
telemt_me_async_recovery_trigger_total 1532
telemt_user_connections_total{user="hello"} 4652
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 9661171 (9.21 MB)
telemt_user_octets_to_client{user="hello"} 357624264 (341.06 MB)
telemt_user_msgs_from_client{user="hello"} 4554
telemt_user_msgs_to_client{user="hello"} 7676
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 72911.2 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3672049
telemt_connections_bad_total 238196
telemt_connections_current 5901
telemt_connections_me_current 5901
telemt_handshake_timeouts_total 75471
telemt_upstream_connect_attempt_total 12711
telemt_upstream_connect_success_total 12632
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 12711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 9090
telemt_me_reconnect_success_total 9028
telemt_me_reader_eof_total 9545
telemt_me_idle_close_by_peer_total 9545
telemt_me_route_drop_no_conn_total 1314960
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3092225
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14781
telemt_desync_full_logged_total 4935
telemt_desync_suppressed_total 9846
telemt_desync_frames_bucket_total{bucket="1_2"} 2925
telemt_desync_frames_bucket_total{bucket="3_10"} 5340
telemt_desync_frames_bucket_total{bucket="gt_10"} 6516
telemt_pool_swap_total 73
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 9162
telemt_me_writer_restored_same_endpoint_total 9011
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 3090206
telemt_user_connections_current{user="hello"} 5901
telemt_user_octets_from_client{user="hello"} 64080273384 (59.68 GB)
telemt_user_octets_to_client{user="hello"} 1581202899716 (1.44 TB)
telemt_user_unique_ips_current{user="hello"} 1858
telemt_user_unique_ips_recent_window{user="hello"} 777
```