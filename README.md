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

# Server Metrics 2026-03-17 20:26:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 92459.3 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1145744
telemt_connections_bad_total 8439
telemt_handshake_timeouts_total 30403
telemt_upstream_connect_attempt_total 21158
telemt_upstream_connect_success_total 20669
telemt_upstream_connect_fail_total 489
telemt_upstream_connect_attempts_per_request{bucket="1"} 21158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 489
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30877
telemt_me_reconnect_success_total 13748
telemt_me_reader_eof_total 14951
telemt_me_idle_close_by_peer_total 14950
telemt_me_route_drop_no_conn_total 513436
telemt_me_route_drop_channel_closed_total 153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1050008
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6988
telemt_desync_full_logged_total 2004
telemt_desync_suppressed_total 4984
telemt_desync_frames_bucket_total{bucket="1_2"} 1879
telemt_desync_frames_bucket_total{bucket="3_10"} 2655
telemt_desync_frames_bucket_total{bucket="gt_10"} 2454
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 14487
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13726
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 739
telemt_user_connections_total{user="hello"} 1044244
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 16537877147 (15.40 GB)
telemt_user_octets_to_client{user="hello"} 365689363375 (340.57 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 92710.3 (25h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1162687
telemt_connections_bad_total 58951
telemt_handshake_timeouts_total 41537
telemt_upstream_connect_attempt_total 456681
telemt_upstream_connect_success_total 455804
telemt_upstream_connect_fail_total 877
telemt_upstream_connect_attempts_per_request{bucket="1"} 456681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 877
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57331
telemt_me_reconnect_success_total 14179
telemt_me_reader_eof_total 16120
telemt_me_idle_close_by_peer_total 16120
telemt_me_route_drop_no_conn_total 291566
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563685
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2426
telemt_desync_full_logged_total 778
telemt_desync_suppressed_total 1648
telemt_desync_frames_bucket_total{bucket="1_2"} 470
telemt_desync_frames_bucket_total{bucket="3_10"} 1020
telemt_desync_frames_bucket_total{bucket="gt_10"} 936
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 15704
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14163
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1525
telemt_user_connections_total{user="hello"} 1000114
telemt_user_connections_current{user="hello"} 1535
telemt_user_octets_from_client{user="hello"} 13847098682 (12.90 GB)
telemt_user_octets_to_client{user="hello"} 322186091970 (300.06 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 92486.3 (25h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 636705
telemt_connections_bad_total 35281
telemt_handshake_timeouts_total 22256
telemt_upstream_connect_attempt_total 22329
telemt_upstream_connect_success_total 22200
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 22329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11966
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38203
telemt_me_reconnect_success_total 17529
telemt_me_reader_eof_total 19139
telemt_me_idle_close_by_peer_total 19132
telemt_me_route_drop_no_conn_total 275257
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549279
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1684
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 1178
telemt_desync_frames_bucket_total{bucket="1_2"} 485
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 536
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 18414
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17517
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 885
telemt_user_connections_total{user="hello"} 547554
telemt_user_connections_current{user="hello"} 1024
telemt_user_octets_from_client{user="hello"} 28179472752 (26.24 GB)
telemt_user_octets_to_client{user="hello"} 224319635208 (208.91 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 92545.9 (25h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1138366
telemt_connections_bad_total 32955
telemt_handshake_timeouts_total 21066
telemt_upstream_connect_attempt_total 81892
telemt_upstream_connect_success_total 81484
telemt_upstream_connect_fail_total 408
telemt_upstream_connect_attempts_per_request{bucket="1"} 81892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11633
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 408
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33796
telemt_me_reconnect_success_total 13487
telemt_me_reader_eof_total 14871
telemt_me_idle_close_by_peer_total 14870
telemt_me_route_drop_no_conn_total 475673
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 926535
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3142
telemt_desync_full_logged_total 1003
telemt_desync_suppressed_total 2139
telemt_desync_frames_bucket_total{bucket="1_2"} 760
telemt_desync_frames_bucket_total{bucket="3_10"} 1346
telemt_desync_frames_bucket_total{bucket="gt_10"} 1036
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14371
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13478
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 884
telemt_user_connections_total{user="hello"} 989055
telemt_user_connections_current{user="hello"} 1315
telemt_user_octets_from_client{user="hello"} 14714537791 (13.70 GB)
telemt_user_octets_to_client{user="hello"} 397955157925 (370.62 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 369
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 92517.6 (25h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 692978
telemt_connections_bad_total 85720
telemt_handshake_timeouts_total 5859
telemt_upstream_connect_attempt_total 40623
telemt_upstream_connect_success_total 40082
telemt_upstream_connect_fail_total 541
telemt_upstream_connect_attempts_per_request{bucket="1"} 40623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 391
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 541
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51453
telemt_me_reconnect_success_total 18968
telemt_me_reader_eof_total 20673
telemt_me_idle_close_by_peer_total 20671
telemt_me_route_drop_no_conn_total 215918
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547332
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2474
telemt_desync_full_logged_total 698
telemt_desync_suppressed_total 1776
telemt_desync_frames_bucket_total{bucket="1_2"} 847
telemt_desync_frames_bucket_total{bucket="3_10"} 992
telemt_desync_frames_bucket_total{bucket="gt_10"} 635
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20309
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18960
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1341
telemt_user_connections_total{user="hello"} 563958
telemt_user_connections_current{user="hello"} 1191
telemt_user_octets_from_client{user="hello"} 11138077512 (10.37 GB)
telemt_user_octets_to_client{user="hello"} 266090261444 (247.82 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 92678.7 (25h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 955222
telemt_connections_bad_total 68168
telemt_handshake_timeouts_total 9104
telemt_upstream_connect_attempt_total 18324
telemt_upstream_connect_success_total 18219
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 18323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9451
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24871
telemt_me_reconnect_success_total 13595
telemt_me_reader_eof_total 14772
telemt_me_idle_close_by_peer_total 14770
telemt_me_route_drop_no_conn_total 671645
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 958717
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1915
telemt_desync_full_logged_total 669
telemt_desync_suppressed_total 1246
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 739
telemt_pool_swap_total 77
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14175
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13581
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 580
telemt_user_connections_total{user="hello"} 821752
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 12683366676 (11.81 GB)
telemt_user_octets_to_client{user="hello"} 354597390828 (330.24 GB)
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 40445.7 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283984
telemt_connections_bad_total 37624
telemt_handshake_timeouts_total 7843
telemt_upstream_connect_attempt_total 16961
telemt_upstream_connect_success_total 16805
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 16961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26210
telemt_me_reconnect_success_total 14620
telemt_me_reader_eof_total 15448
telemt_me_idle_close_by_peer_total 15448
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 69377
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218743
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 657
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 479
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 233
telemt_pool_swap_total 18
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15156
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14592
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 218690
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 20217636469 (18.83 GB)
telemt_user_octets_to_client{user="hello"} 178940975470 (166.65 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 65
```