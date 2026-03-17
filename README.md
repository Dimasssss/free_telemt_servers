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

# Server Metrics 2026-03-17 03:10:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 30336.2 (8h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158317
telemt_connections_bad_total 2379
telemt_handshake_timeouts_total 5488
telemt_upstream_connect_attempt_total 6517
telemt_upstream_connect_success_total 6478
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 6517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4982
telemt_me_reconnect_success_total 4966
telemt_me_reader_eof_total 5282
telemt_me_idle_close_by_peer_total 5282
telemt_me_route_drop_no_conn_total 49690
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143510
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 833
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 545
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 424
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5010
telemt_me_writer_restored_same_endpoint_total 4945
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 143444
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 1925722456 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 64051335180 (59.65 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 30587.5 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88602
telemt_connections_bad_total 1359
telemt_handshake_timeouts_total 3014
telemt_upstream_connect_attempt_total 8388
telemt_upstream_connect_success_total 8278
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 8388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 7939
telemt_me_reconnect_success_total 6772
telemt_me_reader_eof_total 7159
telemt_me_idle_close_by_peer_total 7159
telemt_me_route_drop_no_conn_total 37700
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80602
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 186
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6875
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6756
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 80546
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 1157529908 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 37417124072 (34.85 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 30363.8 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57777
telemt_connections_bad_total 785
telemt_handshake_timeouts_total 1956
telemt_upstream_connect_attempt_total 8159
telemt_upstream_connect_success_total 8113
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 6623
telemt_me_reconnect_success_total 6585
telemt_me_reader_eof_total 7041
telemt_me_idle_close_by_peer_total 7041
telemt_me_route_drop_no_conn_total 18281
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48813
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6669
telemt_me_writer_restored_same_endpoint_total 6574
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 48797
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 5573420200 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 17774893700 (16.55 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 30423.2 (8h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90353
telemt_connections_bad_total 3377
telemt_handshake_timeouts_total 1302
telemt_upstream_connect_attempt_total 7049
telemt_upstream_connect_success_total 6987
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 7049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3668
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 5500
telemt_me_reconnect_success_total 5462
telemt_me_reader_eof_total 5804
telemt_me_idle_close_by_peer_total 5804
telemt_me_route_drop_no_conn_total 31141
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83138
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 153
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5539
telemt_me_writer_restored_same_endpoint_total 5455
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 83123
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 949588688 (905.60 MB)
telemt_user_octets_to_client{user="hello"} 38876681192 (36.21 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 30395.1 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68666
telemt_connections_bad_total 16127
telemt_handshake_timeouts_total 1164
telemt_upstream_connect_attempt_total 8934
telemt_upstream_connect_success_total 8820
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 8934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4712
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_reconnect_attempts_total 9549
telemt_me_reconnect_success_total 7300
telemt_me_reader_eof_total 7702
telemt_me_idle_close_by_peer_total 7702
telemt_me_route_drop_no_conn_total 19765
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49421
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 7480
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 7292
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 49415
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 576777724 (550.06 MB)
telemt_user_octets_to_client{user="hello"} 18554295928 (17.28 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 30556.0 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173446
telemt_connections_bad_total 13977
telemt_handshake_timeouts_total 1103
telemt_upstream_connect_attempt_total 6329
telemt_upstream_connect_success_total 6294
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 6329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 4803
telemt_me_reconnect_success_total 4787
telemt_me_reader_eof_total 5131
telemt_me_idle_close_by_peer_total 5131
telemt_me_route_drop_no_conn_total 180415
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230495
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4856
telemt_me_writer_restored_same_endpoint_total 4777
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 152747
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 2418873768 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 122272980408 (113.88 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 18562.6 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 9344
telemt_upstream_connect_success_total 9344
telemt_upstream_connect_attempts_per_request{bucket="1"} 9344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 8409
telemt_me_reconnect_success_total 8364
telemt_me_reader_eof_total 9176
telemt_me_idle_close_by_peer_total 9176
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 8447
telemt_me_writer_restored_same_endpoint_total 8364
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```