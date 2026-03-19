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

# Server Metrics 2026-03-19 05:17:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 26935.0 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389262
telemt_connections_bad_total 39282
telemt_connections_current 1016
telemt_connections_me_current 1016
telemt_handshake_timeouts_total 20698
telemt_upstream_connect_attempt_total 5184
telemt_upstream_connect_success_total 5099
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 5184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3785
telemt_me_reconnect_success_total 3768
telemt_me_reader_eof_total 3973
telemt_me_idle_close_by_peer_total 3972
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 101418
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284854
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1945
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1408
telemt_desync_frames_bucket_total{bucket="1_2"} 709
telemt_desync_frames_bucket_total{bucket="3_10"} 771
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3799
telemt_me_writer_restored_same_endpoint_total 3751
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 282107
telemt_user_connections_current{user="hello"} 1016
telemt_user_octets_from_client{user="hello"} 3551138932 (3.31 GB)
telemt_user_octets_to_client{user="hello"} 93578919512 (87.15 GB)
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 26939.4 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 756958
telemt_connections_bad_total 45934
telemt_connections_current 2863
telemt_connections_me_current 2863
telemt_handshake_timeouts_total 23024
telemt_upstream_connect_attempt_total 5006
telemt_upstream_connect_success_total 4913
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 5006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_reconnect_attempts_total 3588
telemt_me_reconnect_success_total 3569
telemt_me_reader_eof_total 3770
telemt_me_idle_close_by_peer_total 3770
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 231129
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 628000
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2550
telemt_desync_full_logged_total 861
telemt_desync_suppressed_total 1689
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 951
telemt_desync_frames_bucket_total{bucket="gt_10"} 1107
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3633
telemt_me_writer_restored_same_endpoint_total 3550
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 627902
telemt_user_connections_current{user="hello"} 2863
telemt_user_octets_from_client{user="hello"} 15840953368 (14.75 GB)
telemt_user_octets_to_client{user="hello"} 275915120944 (256.97 GB)
telemt_user_unique_ips_current{user="hello"} 1077
telemt_user_unique_ips_recent_window{user="hello"} 380
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 26936.5 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 644332
telemt_connections_bad_total 115598
telemt_connections_current 2277
telemt_connections_me_current 2277
telemt_handshake_timeouts_total 23059
telemt_upstream_connect_attempt_total 4907
telemt_upstream_connect_success_total 4907
telemt_upstream_connect_attempts_per_request{bucket="1"} 4907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2386
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3577
telemt_me_reconnect_success_total 3563
telemt_me_reader_eof_total 3772
telemt_me_idle_close_by_peer_total 3772
telemt_me_route_drop_no_conn_total 189898
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465050
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2419
telemt_desync_full_logged_total 786
telemt_desync_suppressed_total 1633
telemt_desync_frames_bucket_total{bucket="1_2"} 364
telemt_desync_frames_bucket_total{bucket="3_10"} 857
telemt_desync_frames_bucket_total{bucket="gt_10"} 1198
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3625
telemt_me_writer_restored_same_endpoint_total 3547
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 465036
telemt_user_connections_current{user="hello"} 2277
telemt_user_octets_from_client{user="hello"} 9674580228 (9.01 GB)
telemt_user_octets_to_client{user="hello"} 287295906984 (267.57 GB)
telemt_user_unique_ips_current{user="hello"} 853
telemt_user_unique_ips_recent_window{user="hello"} 293
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 26989.8 (7h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 729926
telemt_connections_bad_total 85837
telemt_connections_current 2096
telemt_connections_me_current 2096
telemt_handshake_timeouts_total 16473
telemt_upstream_connect_attempt_total 4739
telemt_upstream_connect_success_total 4739
telemt_upstream_connect_attempts_per_request{bucket="1"} 4739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 3416
telemt_me_reconnect_success_total 3400
telemt_me_reader_eof_total 3590
telemt_me_idle_close_by_peer_total 3589
telemt_me_route_drop_no_conn_total 207569
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 457955
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1432
telemt_desync_full_logged_total 515
telemt_desync_suppressed_total 917
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 601
telemt_desync_frames_bucket_total{bucket="gt_10"} 567
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 3443
telemt_me_writer_restored_same_endpoint_total 3376
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 456916
telemt_user_connections_current{user="hello"} 2096
telemt_user_octets_from_client{user="hello"} 6983286340 (6.50 GB)
telemt_user_octets_to_client{user="hello"} 175194708128 (163.16 GB)
telemt_user_unique_ips_current{user="hello"} 780
telemt_user_unique_ips_recent_window{user="hello"} 323
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 26933.1 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 839952
telemt_connections_bad_total 232147
telemt_connections_current 2471
telemt_connections_me_current 2471
telemt_handshake_timeouts_total 23114
telemt_upstream_connect_attempt_total 4866
telemt_upstream_connect_success_total 4836
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 3514
telemt_me_reconnect_success_total 3494
telemt_me_reader_eof_total 3695
telemt_me_idle_close_by_peer_total 3695
telemt_me_route_drop_no_conn_total 205003
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 495567
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2315
telemt_desync_full_logged_total 850
telemt_desync_suppressed_total 1465
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 791
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 3530
telemt_me_writer_restored_same_endpoint_total 3470
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 495482
telemt_user_connections_current{user="hello"} 2471
telemt_user_octets_from_client{user="hello"} 14369301900 (13.38 GB)
telemt_user_octets_to_client{user="hello"} 282333717812 (262.94 GB)
telemt_user_unique_ips_current{user="hello"} 905
telemt_user_unique_ips_recent_window{user="hello"} 339
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 26945.0 (7h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146182
telemt_connections_bad_total 10566
telemt_connections_current 559
telemt_connections_me_current 559
telemt_handshake_timeouts_total 980
telemt_upstream_connect_attempt_total 7463
telemt_upstream_connect_success_total 7265
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 7463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3778
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_reconnect_attempts_total 7770
telemt_me_reconnect_success_total 5926
telemt_me_reader_eof_total 6205
telemt_me_idle_close_by_peer_total 6205
telemt_me_route_drop_no_conn_total 58947
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128093
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 178
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 6000
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5896
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 128086
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 2213199020 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 77567094760 (72.24 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 26935.6 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490656
telemt_connections_bad_total 49790
telemt_connections_current 2214
telemt_connections_me_current 2214
telemt_handshake_timeouts_total 24191
telemt_upstream_connect_attempt_total 5516
telemt_upstream_connect_success_total 5515
telemt_upstream_connect_attempts_per_request{bucket="1"} 5515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2588
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4193
telemt_me_reconnect_success_total 4180
telemt_me_reader_eof_total 4406
telemt_me_idle_close_by_peer_total 4406
telemt_me_route_drop_no_conn_total 139236
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401238
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2183
telemt_desync_full_logged_total 804
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 454
telemt_desync_frames_bucket_total{bucket="3_10"} 834
telemt_desync_frames_bucket_total{bucket="gt_10"} 895
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4228
telemt_me_writer_restored_same_endpoint_total 4165
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 401268
telemt_user_connections_current{user="hello"} 2214
telemt_user_octets_from_client{user="hello"} 5173867624 (4.82 GB)
telemt_user_octets_to_client{user="hello"} 235208121728 (219.05 GB)
telemt_user_unique_ips_current{user="hello"} 761
telemt_user_unique_ips_recent_window{user="hello"} 266
```