# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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

# Server Metrics 2026-03-17 19:35:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 89401.9 (24h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1105245
telemt_connections_bad_total 7927
telemt_handshake_timeouts_total 30149
telemt_upstream_connect_attempt_total 20671
telemt_upstream_connect_success_total 20183
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 20671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30520
telemt_me_reconnect_success_total 13393
telemt_me_reader_eof_total 14570
telemt_me_idle_close_by_peer_total 14569
telemt_me_route_drop_no_conn_total 498088
telemt_me_route_drop_channel_closed_total 147
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1011445
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6669
telemt_desync_full_logged_total 1907
telemt_desync_suppressed_total 4762
telemt_desync_frames_bucket_total{bucket="1_2"} 1804
telemt_desync_frames_bucket_total{bucket="3_10"} 2536
telemt_desync_frames_bucket_total{bucket="gt_10"} 2329
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 14124
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13371
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 731
telemt_user_connections_total{user="hello"} 1005691
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 15213674035 (14.17 GB)
telemt_user_octets_to_client{user="hello"} 351077102203 (326.97 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 89653.4 (24h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1091750
telemt_connections_bad_total 56680
telemt_handshake_timeouts_total 38113
telemt_upstream_connect_attempt_total 456272
telemt_upstream_connect_success_total 455399
telemt_upstream_connect_fail_total 873
telemt_upstream_connect_attempts_per_request{bucket="1"} 456272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29887
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 873
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57058
telemt_me_reconnect_success_total 13907
telemt_me_reader_eof_total 15829
telemt_me_idle_close_by_peer_total 15829
telemt_me_route_drop_no_conn_total 269017
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 500898
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1998
telemt_desync_full_logged_total 637
telemt_desync_suppressed_total 1361
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 844
telemt_desync_frames_bucket_total{bucket="gt_10"} 726
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 15424
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13891
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1517
telemt_user_connections_total{user="hello"} 937337
telemt_user_connections_current{user="hello"} 1571
telemt_user_octets_from_client{user="hello"} 13055344250 (12.16 GB)
telemt_user_octets_to_client{user="hello"} 282768428678 (263.35 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 89432.6 (24h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 576496
telemt_connections_bad_total 22325
telemt_handshake_timeouts_total 21922
telemt_upstream_connect_attempt_total 21854
telemt_upstream_connect_success_total 21727
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 21854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 37859
telemt_me_reconnect_success_total 17188
telemt_me_reader_eof_total 18776
telemt_me_idle_close_by_peer_total 18769
telemt_me_route_drop_no_conn_total 257547
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 504287
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1471
telemt_desync_full_logged_total 430
telemt_desync_suppressed_total 1041
telemt_desync_frames_bucket_total{bucket="1_2"} 432
telemt_desync_frames_bucket_total{bucket="3_10"} 595
telemt_desync_frames_bucket_total{bucket="gt_10"} 444
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 18063
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17176
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 875
telemt_user_connections_total{user="hello"} 502540
telemt_user_connections_current{user="hello"} 1224
telemt_user_octets_from_client{user="hello"} 27540860928 (25.65 GB)
telemt_user_octets_to_client{user="hello"} 196262720456 (182.78 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 89488.7 (24h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1076039
telemt_connections_bad_total 27395
telemt_handshake_timeouts_total 20521
telemt_upstream_connect_attempt_total 81461
telemt_upstream_connect_success_total 81057
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 81461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11416
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33497
telemt_me_reconnect_success_total 13193
telemt_me_reader_eof_total 14555
telemt_me_idle_close_by_peer_total 14554
telemt_me_route_drop_no_conn_total 444576
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 872143
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2904
telemt_desync_full_logged_total 938
telemt_desync_suppressed_total 1966
telemt_desync_frames_bucket_total{bucket="1_2"} 690
telemt_desync_frames_bucket_total{bucket="3_10"} 1265
telemt_desync_frames_bucket_total{bucket="gt_10"} 949
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14069
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13184
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 876
telemt_user_connections_total{user="hello"} 935206
telemt_user_connections_current{user="hello"} 1367
telemt_user_octets_from_client{user="hello"} 13289675283 (12.38 GB)
telemt_user_octets_to_client{user="hello"} 354740634741 (330.38 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 382
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 89460.5 (24h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 629694
telemt_connections_bad_total 76286
telemt_handshake_timeouts_total 5399
telemt_upstream_connect_attempt_total 40117
telemt_upstream_connect_success_total 39584
telemt_upstream_connect_fail_total 533
telemt_upstream_connect_attempts_per_request{bucket="1"} 40117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 533
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51084
telemt_me_reconnect_success_total 18601
telemt_me_reader_eof_total 20285
telemt_me_idle_close_by_peer_total 20283
telemt_me_route_drop_no_conn_total 195606
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 496137
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2241
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1629
telemt_desync_frames_bucket_total{bucket="1_2"} 787
telemt_desync_frames_bucket_total{bucket="3_10"} 889
telemt_desync_frames_bucket_total{bucket="gt_10"} 565
telemt_pool_swap_total 44
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19934
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18593
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1333
telemt_user_connections_total{user="hello"} 512787
telemt_user_connections_current{user="hello"} 1227
telemt_user_octets_from_client{user="hello"} 10321697712 (9.61 GB)
telemt_user_octets_to_client{user="hello"} 238671299464 (222.28 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 89621.7 (24h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 918012
telemt_connections_bad_total 61559
telemt_handshake_timeouts_total 8922
telemt_upstream_connect_attempt_total 17807
telemt_upstream_connect_success_total 17707
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 17807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24488
telemt_me_reconnect_success_total 13214
telemt_me_reader_eof_total 14365
telemt_me_idle_close_by_peer_total 14363
telemt_me_route_drop_no_conn_total 658352
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 932821
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1840
telemt_desync_full_logged_total 639
telemt_desync_suppressed_total 1201
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 691
telemt_pool_swap_total 74
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13788
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13200
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 795860
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 12219805344 (11.38 GB)
telemt_user_octets_to_client{user="hello"} 344636659796 (320.97 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 37388.6 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247602
telemt_connections_bad_total 32614
telemt_handshake_timeouts_total 6413
telemt_upstream_connect_attempt_total 16172
telemt_upstream_connect_success_total 16029
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 16172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 25562
telemt_me_reconnect_success_total 13975
telemt_me_reader_eof_total 14783
telemt_me_idle_close_by_peer_total 14783
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 59800
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190062
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 579
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 428
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 17
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14502
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13950
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 190005
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 18715559993 (17.43 GB)
telemt_user_octets_to_client{user="hello"} 159687027906 (148.72 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 79
```