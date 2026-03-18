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

# Server Metrics 2026-03-18 15:58:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2011.1 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68623
telemt_connections_bad_total 8580
telemt_handshake_timeouts_total 3209
telemt_upstream_connect_attempt_total 306
telemt_upstream_connect_success_total 305
telemt_upstream_connect_attempts_per_request{bucket="1"} 305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 150
telemt_me_reconnect_success_total 148
telemt_me_reader_eof_total 136
telemt_me_idle_close_by_peer_total 136
telemt_me_route_drop_no_conn_total 22285
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52845
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 342
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 264
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 152
telemt_me_writer_restored_same_endpoint_total 137
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 52824
telemt_user_connections_current{user="hello"} 1471
telemt_user_octets_from_client{user="hello"} 861794564 (821.87 MB)
telemt_user_octets_to_client{user="hello"} 17036297732 (15.87 GB)
telemt_user_unique_ips_current{user="hello"} 506
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 6840.2 (1h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 735518
telemt_connections_bad_total 51006
telemt_connections_current 3316
telemt_connections_me_current 3316
telemt_handshake_timeouts_total 13309
telemt_upstream_connect_attempt_total 1212
telemt_upstream_connect_success_total 1204
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 829
telemt_me_reconnect_success_total 821
telemt_me_reader_eof_total 744
telemt_me_idle_close_by_peer_total 743
telemt_me_route_drop_no_conn_total 727961
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636158
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1649
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 1138
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 668
telemt_desync_frames_bucket_total{bucket="gt_10"} 640
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 750
telemt_me_writer_restored_same_endpoint_total 819
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 635361
telemt_user_connections_current{user="hello"} 3316
telemt_user_octets_from_client{user="hello"} 5985995964 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 173575364200 (161.65 GB)
telemt_user_unique_ips_current{user="hello"} 1099
telemt_user_unique_ips_recent_window{user="hello"} 459
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 6768.9 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491213
telemt_connections_bad_total 32582
telemt_connections_current 2898
telemt_connections_me_current 2898
telemt_handshake_timeouts_total 10008
telemt_upstream_connect_attempt_total 947
telemt_upstream_connect_success_total 942
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 571
telemt_me_reconnect_success_total 565
telemt_me_reader_eof_total 583
telemt_me_idle_close_by_peer_total 583
telemt_me_route_drop_no_conn_total 268605
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 414443
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1506
telemt_desync_full_logged_total 427
telemt_desync_suppressed_total 1079
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 563
telemt_desync_frames_bucket_total{bucket="gt_10"} 593
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_restored_same_endpoint_total 548
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 414188
telemt_user_connections_current{user="hello"} 2898
telemt_user_octets_from_client{user="hello"} 8211245140 (7.65 GB)
telemt_user_octets_to_client{user="hello"} 156517712928 (145.77 GB)
telemt_user_unique_ips_current{user="hello"} 954
telemt_user_unique_ips_recent_window{user="hello"} 396
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 7483.2 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 670359
telemt_connections_bad_total 8636
telemt_connections_current 2495
telemt_connections_me_current 2495
telemt_handshake_timeouts_total 9070
telemt_upstream_connect_attempt_total 1251
telemt_upstream_connect_success_total 1241
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 817
telemt_me_reconnect_success_total 808
telemt_me_reader_eof_total 797
telemt_me_idle_close_by_peer_total 796
telemt_me_route_drop_no_conn_total 1096229
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 609319
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2333
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 1755
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 1071
telemt_desync_frames_bucket_total{bucket="gt_10"} 756
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 795
telemt_me_writer_restored_same_endpoint_total 797
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 609318
telemt_user_connections_current{user="hello"} 2495
telemt_user_octets_from_client{user="hello"} 4417120944 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 114419859860 (106.56 GB)
telemt_user_unique_ips_current{user="hello"} 810
telemt_user_unique_ips_recent_window{user="hello"} 322
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1998.0 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152782
telemt_connections_bad_total 27760
telemt_handshake_timeouts_total 2016
telemt_upstream_connect_attempt_total 349
telemt_upstream_connect_success_total 339
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 185
telemt_me_reconnect_success_total 182
telemt_me_reader_eof_total 151
telemt_me_idle_close_by_peer_total 151
telemt_me_route_drop_no_conn_total 55775
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111956
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 342
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 228
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 105
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 172
telemt_me_writer_restored_same_endpoint_total 156
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_user_connections_total{user="hello"} 111744
telemt_user_connections_current{user="hello"} 3059
telemt_user_octets_from_client{user="hello"} 1998573640 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 41270544632 (38.44 GB)
telemt_user_unique_ips_current{user="hello"} 986
telemt_user_unique_ips_recent_window{user="hello"} 421
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 6933.3 (1h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136820
telemt_connections_bad_total 5710
telemt_connections_current 898
telemt_connections_me_current 898
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1234
telemt_upstream_connect_attempt_total 5314
telemt_upstream_connect_success_total 5305
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 330558
telemt_me_reconnect_success_total 1101
telemt_me_reader_eof_total 1032
telemt_me_idle_close_by_peer_total 1032
telemt_me_route_drop_no_conn_total 76442
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119684
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 243
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1028
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1090
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 123431
telemt_user_connections_current{user="hello"} 898
telemt_user_octets_from_client{user="hello"} 1899459837 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 26171390989 (24.37 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 6002.4 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378398
telemt_connections_bad_total 14638
telemt_connections_current 2708
telemt_connections_me_current 2708
telemt_handshake_timeouts_total 4185
telemt_upstream_connect_attempt_total 1144
telemt_upstream_connect_success_total 1144
telemt_upstream_connect_attempts_per_request{bucket="1"} 1144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 15097
telemt_me_reconnect_success_total 805
telemt_me_reader_eof_total 710
telemt_me_idle_close_by_peer_total 710
telemt_me_route_drop_no_conn_total 246099
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325567
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 816
telemt_desync_full_logged_total 310
telemt_desync_suppressed_total 506
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 364
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 720
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 744
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 325857
telemt_user_connections_current{user="hello"} 2708
telemt_user_octets_from_client{user="hello"} 4613822368 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 134783373976 (125.53 GB)
telemt_user_unique_ips_current{user="hello"} 794
telemt_user_unique_ips_recent_window{user="hello"} 348
```