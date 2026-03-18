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

# Server Metrics 2026-03-18 23:55:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 7614.8 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88379
telemt_connections_bad_total 9259
telemt_connections_current 615
telemt_connections_me_current 615
telemt_handshake_timeouts_total 970
telemt_upstream_connect_attempt_total 1419
telemt_upstream_connect_success_total 1396
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 990
telemt_me_reconnect_success_total 987
telemt_me_reader_eof_total 1013
telemt_me_idle_close_by_peer_total 1013
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 28639
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74647
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 400
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 986
telemt_me_writer_restored_same_endpoint_total 975
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 71891
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 713471676 (680.42 MB)
telemt_user_octets_to_client{user="hello"} 30383300740 (28.30 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 7618.7 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196873
telemt_connections_bad_total 15712
telemt_connections_current 1577
telemt_connections_me_current 1577
telemt_handshake_timeouts_total 1718
telemt_upstream_connect_attempt_total 1469
telemt_upstream_connect_success_total 1436
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 1469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 1023
telemt_me_reconnect_success_total 1022
telemt_me_reader_eof_total 1064
telemt_me_idle_close_by_peer_total 1064
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 61204
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168671
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 692
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 461
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1040
telemt_me_writer_restored_same_endpoint_total 1011
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 168748
telemt_user_connections_current{user="hello"} 1577
telemt_user_octets_from_client{user="hello"} 10438331552 (9.72 GB)
telemt_user_octets_to_client{user="hello"} 65389776868 (60.90 GB)
telemt_user_unique_ips_current{user="hello"} 630
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 7615.7 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153539
telemt_connections_bad_total 23130
telemt_connections_current 1106
telemt_connections_me_current 1106
telemt_handshake_timeouts_total 4342
telemt_upstream_connect_attempt_total 1488
telemt_upstream_connect_success_total 1488
telemt_upstream_connect_attempts_per_request{bucket="1"} 1488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 731
telemt_me_reconnect_attempts_total 1076
telemt_me_reconnect_success_total 1073
telemt_me_reader_eof_total 1113
telemt_me_idle_close_by_peer_total 1113
telemt_me_route_drop_no_conn_total 52400
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121442
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 507
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 308
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1087
telemt_me_writer_restored_same_endpoint_total 1057
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 121444
telemt_user_connections_current{user="hello"} 1106
telemt_user_octets_from_client{user="hello"} 1673153680 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 73768042040 (68.70 GB)
telemt_user_unique_ips_current{user="hello"} 522
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 7669.1 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164010
telemt_connections_bad_total 25050
telemt_connections_current 1002
telemt_connections_me_current 1002
telemt_handshake_timeouts_total 3247
telemt_upstream_connect_attempt_total 1421
telemt_upstream_connect_success_total 1421
telemt_upstream_connect_attempts_per_request{bucket="1"} 1421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 1012
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 1042
telemt_me_idle_close_by_peer_total 1042
telemt_me_route_drop_no_conn_total 63530
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126744
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 305
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 190
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1021
telemt_me_writer_restored_same_endpoint_total 984
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 126672
telemt_user_connections_current{user="hello"} 1002
telemt_user_octets_from_client{user="hello"} 1425717364 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 48193349284 (44.88 GB)
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 7612.4 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168693
telemt_connections_bad_total 7563
telemt_connections_current 1169
telemt_connections_me_current 1169
telemt_handshake_timeouts_total 5775
telemt_upstream_connect_attempt_total 1405
telemt_upstream_connect_success_total 1397
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 984
telemt_me_reconnect_success_total 979
telemt_me_reader_eof_total 1008
telemt_me_idle_close_by_peer_total 1008
telemt_me_route_drop_no_conn_total 53590
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132278
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 572
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 343
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 199
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 982
telemt_me_writer_restored_same_endpoint_total 955
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 132222
telemt_user_connections_current{user="hello"} 1169
telemt_user_octets_from_client{user="hello"} 1684616464 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 82479872108 (76.82 GB)
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 7624.0 (2h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40093
telemt_connections_bad_total 7045
telemt_connections_current 369
telemt_connections_me_current 369
telemt_handshake_timeouts_total 105
telemt_upstream_connect_attempt_total 2390
telemt_upstream_connect_success_total 2318
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 2390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 3734
telemt_me_reconnect_success_total 1907
telemt_me_reader_eof_total 1966
telemt_me_idle_close_by_peer_total 1966
telemt_me_route_drop_no_conn_total 14145
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32013
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1942
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 1877
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 32014
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 390497052 (372.41 MB)
telemt_user_octets_to_client{user="hello"} 23900599512 (22.26 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 7614.9 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125019
telemt_connections_bad_total 16056
telemt_connections_current 1040
telemt_connections_me_current 1040
telemt_handshake_timeouts_total 4408
telemt_upstream_connect_attempt_total 1516
telemt_upstream_connect_success_total 1516
telemt_upstream_connect_attempts_per_request{bucket="1"} 1516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 723
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1103
telemt_me_reconnect_success_total 1100
telemt_me_reader_eof_total 1141
telemt_me_idle_close_by_peer_total 1141
telemt_me_route_drop_no_conn_total 37731
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102089
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 707
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 438
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 296
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1112
telemt_me_writer_restored_same_endpoint_total 1085
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 102114
telemt_user_connections_current{user="hello"} 1040
telemt_user_octets_from_client{user="hello"} 1006648020 (960.01 MB)
telemt_user_octets_to_client{user="hello"} 53844393712 (50.15 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 105
```