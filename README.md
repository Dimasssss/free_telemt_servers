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

# Server Metrics 2026-03-17 05:13:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 37676.7 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204171
telemt_connections_bad_total 3129
telemt_handshake_timeouts_total 7132
telemt_upstream_connect_attempt_total 7961
telemt_upstream_connect_success_total 7918
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6074
telemt_me_reconnect_success_total 6052
telemt_me_reader_eof_total 6436
telemt_me_idle_close_by_peer_total 6436
telemt_me_route_drop_no_conn_total 64505
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184981
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1181
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 768
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 602
telemt_desync_frames_bucket_total{bucket="gt_10"} 313
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6111
telemt_me_writer_restored_same_endpoint_total 6031
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 184781
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 2591831468 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 83984288740 (78.22 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 37927.9 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119538
telemt_connections_bad_total 2190
telemt_handshake_timeouts_total 8705
telemt_upstream_connect_attempt_total 10524
telemt_upstream_connect_success_total 10387
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 10524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 9661
telemt_me_reconnect_success_total 8489
telemt_me_reader_eof_total 8982
telemt_me_idle_close_by_peer_total 8982
telemt_me_route_drop_no_conn_total 46665
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103990
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 292
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 8604
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 8473
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 103992
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 1369577836 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 45535159520 (42.41 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 37704.3 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73005
telemt_connections_bad_total 1022
telemt_handshake_timeouts_total 2478
telemt_upstream_connect_attempt_total 10095
telemt_upstream_connect_success_total 10040
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 8201
telemt_me_reconnect_success_total 8158
telemt_me_reader_eof_total 8735
telemt_me_idle_close_by_peer_total 8735
telemt_me_route_drop_no_conn_total 24371
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62387
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 8257
telemt_me_writer_restored_same_endpoint_total 8147
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 62371
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 5943033104 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 20398473644 (19.00 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 37763.4 (10h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119634
telemt_connections_bad_total 3654
telemt_handshake_timeouts_total 3456
telemt_upstream_connect_attempt_total 8598
telemt_upstream_connect_success_total 8524
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 8598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4484
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 6656
telemt_me_reconnect_success_total 6605
telemt_me_reader_eof_total 7034
telemt_me_idle_close_by_peer_total 7034
telemt_me_route_drop_no_conn_total 40255
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108982
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 190
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 129
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6703
telemt_me_writer_restored_same_endpoint_total 6598
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 109000
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 1211785886 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 51160148017 (47.65 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 37735.4 (10h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90085
telemt_connections_bad_total 23916
telemt_handshake_timeouts_total 1500
telemt_upstream_connect_attempt_total 11217
telemt_upstream_connect_success_total 11073
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 11217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_reconnect_attempts_total 11353
telemt_me_reconnect_success_total 9094
telemt_me_reader_eof_total 9609
telemt_me_idle_close_by_peer_total 9609
telemt_me_route_drop_no_conn_total 24708
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62180
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 9285
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 9086
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 62278
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 706947851 (674.20 MB)
telemt_user_octets_to_client{user="hello"} 26601639074 (24.77 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 37896.7 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225230
telemt_connections_bad_total 29468
telemt_handshake_timeouts_total 1554
telemt_upstream_connect_attempt_total 7822
telemt_upstream_connect_success_total 7781
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 7822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4057
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5902
telemt_me_reconnect_success_total 5876
telemt_me_reader_eof_total 6303
telemt_me_idle_close_by_peer_total 6303
telemt_me_route_drop_no_conn_total 197111
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264831
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 211
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5963
telemt_me_writer_restored_same_endpoint_total 5866
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 187084
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 2918295416 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 143556891308 (133.70 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 25903.0 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 13001
telemt_upstream_connect_success_total 13001
telemt_upstream_connect_attempts_per_request{bucket="1"} 13001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 11719
telemt_me_reconnect_success_total 11656
telemt_me_reader_eof_total 12801
telemt_me_idle_close_by_peer_total 12801
telemt_me_route_drop_no_conn_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 11766
telemt_me_writer_restored_same_endpoint_total 11656
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 159
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 158038780 (150.72 MB)
telemt_user_octets_to_client{user="hello"} 89191424 (85.06 MB)
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```