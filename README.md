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

# Server Metrics 2026-03-17 05:08:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 37359.0 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201382
telemt_connections_bad_total 3102
telemt_handshake_timeouts_total 7099
telemt_upstream_connect_attempt_total 7937
telemt_upstream_connect_success_total 7894
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6050
telemt_me_reconnect_success_total 6029
telemt_me_reader_eof_total 6412
telemt_me_idle_close_by_peer_total 6412
telemt_me_route_drop_no_conn_total 63735
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182656
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1167
telemt_desync_full_logged_total 406
telemt_desync_suppressed_total 761
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 594
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6087
telemt_me_writer_restored_same_endpoint_total 6008
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 182463
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 2573615768 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 82805239824 (77.12 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 37610.4 (10h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116486
telemt_connections_bad_total 2186
telemt_handshake_timeouts_total 7070
telemt_upstream_connect_attempt_total 10434
telemt_upstream_connect_success_total 10300
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 10434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_reconnect_attempts_total 9617
telemt_me_reconnect_success_total 8445
telemt_me_reader_eof_total 8934
telemt_me_idle_close_by_peer_total 8934
telemt_me_route_drop_no_conn_total 46219
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102603
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 288
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 8560
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 8429
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 102605
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 1362363544 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 45185833564 (42.08 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 37386.7 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72240
telemt_connections_bad_total 1021
telemt_handshake_timeouts_total 2465
telemt_upstream_connect_attempt_total 10050
telemt_upstream_connect_success_total 9995
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 8156
telemt_me_reconnect_success_total 8113
telemt_me_reader_eof_total 8690
telemt_me_idle_close_by_peer_total 8690
telemt_me_route_drop_no_conn_total 24180
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61690
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
telemt_me_writer_removed_unexpected_total 8212
telemt_me_writer_restored_same_endpoint_total 8102
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 61674
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 5924247292 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 20095276620 (18.72 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 37445.9 (10h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117938
telemt_connections_bad_total 3653
telemt_handshake_timeouts_total 3395
telemt_upstream_connect_attempt_total 8569
telemt_upstream_connect_success_total 8495
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 8569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4467
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 6627
telemt_me_reconnect_success_total 6576
telemt_me_reader_eof_total 7005
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 39743
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107401
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 182
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6674
telemt_me_writer_restored_same_endpoint_total 6569
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 107419
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 1191404846 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 50278715729 (46.83 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 37431.8 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88747
telemt_connections_bad_total 23298
telemt_handshake_timeouts_total 1468
telemt_upstream_connect_attempt_total 11076
telemt_upstream_connect_success_total 10933
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 11074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_reconnect_attempts_total 11303
telemt_me_reconnect_success_total 9044
telemt_me_reader_eof_total 9561
telemt_me_idle_close_by_peer_total 9561
telemt_me_route_drop_no_conn_total 24419
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61606
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
telemt_me_writer_removed_unexpected_total 9238
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 9036
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 61615
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 703437638 (670.85 MB)
telemt_user_octets_to_client{user="hello"} 26181445189 (24.38 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 27
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 37578.8 (10h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223131
telemt_connections_bad_total 29468
telemt_handshake_timeouts_total 1541
telemt_upstream_connect_attempt_total 7757
telemt_upstream_connect_success_total 7716
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 7757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5880
telemt_me_reconnect_success_total 5854
telemt_me_reader_eof_total 6279
telemt_me_idle_close_by_peer_total 6279
telemt_me_route_drop_no_conn_total 196279
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262965
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 197
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 5939
telemt_me_writer_restored_same_endpoint_total 5844
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 185217
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 2898634020 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 143099049412 (133.27 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 25585.3 (7h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326
telemt_connections_bad_total 181
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 12874
telemt_upstream_connect_success_total 12874
telemt_upstream_connect_attempts_per_request{bucket="1"} 12874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 11592
telemt_me_reconnect_success_total 11529
telemt_me_reader_eof_total 12674
telemt_me_idle_close_by_peer_total 12674
telemt_me_route_drop_no_conn_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 11639
telemt_me_writer_restored_same_endpoint_total 11529
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 142
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 157922656 (150.61 MB)
telemt_user_octets_to_client{user="hello"} 88883204 (84.77 MB)
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```