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

# Server Metrics 2026-03-17 21:22:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 95829.2 (26h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1179264
telemt_connections_bad_total 8636
telemt_handshake_timeouts_total 31509
telemt_upstream_connect_attempt_total 21784
telemt_upstream_connect_success_total 21293
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 21784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31329
telemt_me_reconnect_success_total 14199
telemt_me_reader_eof_total 15433
telemt_me_idle_close_by_peer_total 15432
telemt_me_route_drop_no_conn_total 526476
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1080845
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7170
telemt_desync_full_logged_total 2063
telemt_desync_suppressed_total 5107
telemt_desync_frames_bucket_total{bucket="1_2"} 1921
telemt_desync_frames_bucket_total{bucket="3_10"} 2718
telemt_desync_frames_bucket_total{bucket="gt_10"} 2531
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 14944
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14177
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 745
telemt_user_connections_total{user="hello"} 1075078
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 19200319143 (17.88 GB)
telemt_user_octets_to_client{user="hello"} 381950823287 (355.72 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 96080.6 (26h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1227794
telemt_connections_bad_total 59576
telemt_handshake_timeouts_total 44009
telemt_upstream_connect_attempt_total 457268
telemt_upstream_connect_success_total 456378
telemt_upstream_connect_fail_total 890
telemt_upstream_connect_attempts_per_request{bucket="1"} 457268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 890
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57733
telemt_me_reconnect_success_total 14580
telemt_me_reader_eof_total 16546
telemt_me_idle_close_by_peer_total 16546
telemt_me_route_drop_no_conn_total 312378
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 623537
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2760
telemt_desync_full_logged_total 880
telemt_desync_suppressed_total 1880
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 1153
telemt_desync_frames_bucket_total{bucket="gt_10"} 1086
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16110
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14564
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1530
telemt_user_connections_total{user="hello"} 1059968
telemt_user_connections_current{user="hello"} 1200
telemt_user_octets_from_client{user="hello"} 14683808978 (13.68 GB)
telemt_user_octets_to_client{user="hello"} 353445011190 (329.17 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 95856.8 (26h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691220
telemt_connections_bad_total 39731
telemt_handshake_timeouts_total 22612
telemt_upstream_connect_attempt_total 22918
telemt_upstream_connect_success_total 22785
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 22918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12260
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38615
telemt_me_reconnect_success_total 17940
telemt_me_reader_eof_total 19580
telemt_me_idle_close_by_peer_total 19573
telemt_me_route_drop_no_conn_total 292095
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595792
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1903
telemt_desync_full_logged_total 580
telemt_desync_suppressed_total 1323
telemt_desync_frames_bucket_total{bucket="1_2"} 530
telemt_desync_frames_bucket_total{bucket="3_10"} 750
telemt_desync_frames_bucket_total{bucket="gt_10"} 623
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 18832
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17928
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 892
telemt_user_connections_total{user="hello"} 594063
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 29902809964 (27.85 GB)
telemt_user_octets_to_client{user="hello"} 254906170288 (237.40 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 95916.0 (26h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1192725
telemt_connections_bad_total 37448
telemt_handshake_timeouts_total 21288
telemt_upstream_connect_attempt_total 82547
telemt_upstream_connect_success_total 82123
telemt_upstream_connect_fail_total 424
telemt_upstream_connect_attempts_per_request{bucket="1"} 82547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 424
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 34268
telemt_me_reconnect_success_total 13949
telemt_me_reader_eof_total 15394
telemt_me_idle_close_by_peer_total 15392
telemt_me_route_drop_no_conn_total 495414
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 974489
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3355
telemt_desync_full_logged_total 1074
telemt_desync_suppressed_total 2281
telemt_desync_frames_bucket_total{bucket="1_2"} 828
telemt_desync_frames_bucket_total{bucket="3_10"} 1420
telemt_desync_frames_bucket_total{bucket="gt_10"} 1107
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14845
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13940
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 896
telemt_user_connections_total{user="hello"} 1036999
telemt_user_connections_current{user="hello"} 1014
telemt_user_octets_from_client{user="hello"} 15507019627 (14.44 GB)
telemt_user_octets_to_client{user="hello"} 438425963665 (408.32 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 95888.0 (26h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 746890
telemt_connections_bad_total 91195
telemt_handshake_timeouts_total 6309
telemt_upstream_connect_attempt_total 41340
telemt_upstream_connect_success_total 40789
telemt_upstream_connect_fail_total 551
telemt_upstream_connect_attempts_per_request{bucket="1"} 41340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 396
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 551
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51987
telemt_me_reconnect_success_total 19502
telemt_me_reader_eof_total 21229
telemt_me_idle_close_by_peer_total 21227
telemt_me_route_drop_no_conn_total 234265
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 593185
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2698
telemt_desync_full_logged_total 784
telemt_desync_suppressed_total 1914
telemt_desync_frames_bucket_total{bucket="1_2"} 884
telemt_desync_frames_bucket_total{bucket="3_10"} 1080
telemt_desync_frames_bucket_total{bucket="gt_10"} 734
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20847
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19494
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1345
telemt_user_connections_total{user="hello"} 609799
telemt_user_connections_current{user="hello"} 1040
telemt_user_octets_from_client{user="hello"} 11863562528 (11.05 GB)
telemt_user_octets_to_client{user="hello"} 298783407912 (278.26 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 96049.0 (26h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 987828
telemt_connections_bad_total 72525
telemt_handshake_timeouts_total 9326
telemt_upstream_connect_attempt_total 18975
telemt_upstream_connect_success_total 18863
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 18975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9747
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25342
telemt_me_reconnect_success_total 14065
telemt_me_reader_eof_total 15280
telemt_me_idle_close_by_peer_total 15278
telemt_me_route_drop_no_conn_total 683145
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 981892
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2018
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 1313
telemt_desync_frames_bucket_total{bucket="1_2"} 454
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 796
telemt_pool_swap_total 81
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14651
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14051
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 586
telemt_user_connections_total{user="hello"} 844924
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 13148053932 (12.25 GB)
telemt_user_octets_to_client{user="hello"} 362652820312 (337.75 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 43816.1 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324167
telemt_connections_bad_total 41889
telemt_handshake_timeouts_total 9901
telemt_upstream_connect_attempt_total 17638
telemt_upstream_connect_success_total 17475
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 17638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26707
telemt_me_reconnect_success_total 15113
telemt_me_reader_eof_total 15971
telemt_me_idle_close_by_peer_total 15971
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 79718
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248045
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 790
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 561
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 304
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15653
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15085
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 247987
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 20936942481 (19.50 GB)
telemt_user_octets_to_client{user="hello"} 207944765218 (193.66 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 65
```