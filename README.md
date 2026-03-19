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

# Server Metrics 2026-03-19 12:52:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 660.8 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26621
telemt_connections_bad_total 1066
telemt_connections_current 1657
telemt_connections_me_current 1657
telemt_handshake_timeouts_total 561
telemt_upstream_connect_attempt_total 102
telemt_upstream_connect_success_total 84
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 29
telemt_me_reconnect_success_total 13
telemt_me_route_drop_no_conn_total 11789
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23932
telemt_me_writer_pick_total{mode="p2c",result="full"} 54
telemt_me_writer_pick_total{mode="p2c",result="closed"} 152
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 2
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 220
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 23560
telemt_user_connections_current{user="hello"} 1657
telemt_user_octets_from_client{user="hello"} 485055544 (462.59 MB)
telemt_user_octets_to_client{user="hello"} 7389085860 (6.88 GB)
telemt_user_unique_ips_current{user="hello"} 554
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 570.4 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66223
telemt_connections_bad_total 1226
telemt_connections_current 3535
telemt_connections_me_current 3535
telemt_handshake_timeouts_total 442
telemt_upstream_connect_attempt_total 1446
telemt_upstream_connect_success_total 1442
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 161
telemt_me_reconnect_success_total 159
telemt_me_reader_eof_total 98
telemt_me_idle_close_by_peer_total 98
telemt_me_route_drop_no_conn_total 38081
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60022
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 148
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 121
telemt_me_writer_restored_same_endpoint_total 104
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_user_connections_total{user="hello"} 61096
telemt_user_connections_current{user="hello"} 3535
telemt_user_octets_from_client{user="hello"} 428056066 (408.23 MB)
telemt_user_octets_to_client{user="hello"} 12407663198 (11.56 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1289
telemt_user_unique_ips_recent_window{user="hello"} 832
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 548.7 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70326
telemt_connections_bad_total 3110
telemt_connections_current 3030
telemt_connections_me_current 3030
telemt_handshake_timeouts_total 634
telemt_upstream_connect_attempt_total 181
telemt_upstream_connect_success_total 180
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 115
telemt_me_reconnect_success_total 115
telemt_me_reader_eof_total 29
telemt_me_idle_close_by_peer_total 29
telemt_me_route_drop_no_conn_total 31393
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47331
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 162
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 51
telemt_me_writer_restored_same_endpoint_total 114
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5542
telemt_user_connections_total{user="hello"} 47180
telemt_user_connections_current{user="hello"} 3030
telemt_user_octets_from_client{user="hello"} 292187220 (278.65 MB)
telemt_user_octets_to_client{user="hello"} 11060966224 (10.30 GB)
telemt_user_unique_ips_current{user="hello"} 1060
telemt_user_unique_ips_recent_window{user="hello"} 489
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 536.5 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53700
telemt_connections_bad_total 7969
telemt_connections_current 2877
telemt_connections_me_current 2877
telemt_handshake_timeouts_total 873
telemt_upstream_connect_attempt_total 149
telemt_upstream_connect_success_total 145
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 63
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 82
telemt_me_reconnect_success_total 82
telemt_me_reader_eof_total 34
telemt_me_idle_close_by_peer_total 34
telemt_me_route_drop_no_conn_total 19173
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41133
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 57
telemt_me_writer_restored_same_endpoint_total 79
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_user_connections_total{user="hello"} 41005
telemt_user_connections_current{user="hello"} 2877
telemt_user_octets_from_client{user="hello"} 414413260 (395.22 MB)
telemt_user_octets_to_client{user="hello"} 8916028648 (8.30 GB)
telemt_user_unique_ips_current{user="hello"} 956
telemt_user_unique_ips_recent_window{user="hello"} 431
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 54259.7 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3605332
telemt_connections_bad_total 724541
telemt_connections_current 3521
telemt_connections_me_current 3521
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 71186
telemt_upstream_connect_attempt_total 61486
telemt_upstream_connect_success_total 59005
telemt_upstream_connect_fail_total 2481
telemt_upstream_connect_attempts_per_request{bucket="1"} 61486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2481
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70149
telemt_me_reconnect_success_total 7099
telemt_me_reader_eof_total 7418
telemt_me_idle_close_by_peer_total 7415
telemt_me_route_drop_no_conn_total 1606434
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2410724
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10316
telemt_desync_full_logged_total 3210
telemt_desync_suppressed_total 7106
telemt_desync_frames_bucket_total{bucket="1_2"} 1879
telemt_desync_frames_bucket_total{bucket="3_10"} 4381
telemt_desync_frames_bucket_total{bucket="gt_10"} 4056
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 7217
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7075
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 2459616
telemt_user_connections_current{user="hello"} 3521
telemt_user_octets_from_client{user="hello"} 39040387927 (36.36 GB)
telemt_user_octets_to_client{user="hello"} 899214879020 (837.46 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1130
telemt_user_unique_ips_recent_window{user="hello"} 519
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 501.1 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13907
telemt_connections_bad_total 373
telemt_connections_current 917
telemt_connections_me_current 917
telemt_handshake_timeouts_total 65
telemt_upstream_connect_attempt_total 81
telemt_upstream_connect_success_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 81
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_me_reconnect_attempts_total 15
telemt_me_reconnect_success_total 15
telemt_me_route_drop_no_conn_total 10949
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12927
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 21
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 367
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 12926
telemt_user_connections_current{user="hello"} 917
telemt_user_octets_from_client{user="hello"} 99851768 (95.23 MB)
telemt_user_octets_to_client{user="hello"} 2115246332 (1.97 GB)
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 500.9 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37873
telemt_connections_bad_total 2704
telemt_connections_current 3066
telemt_connections_me_current 3066
telemt_handshake_timeouts_total 186
telemt_upstream_connect_attempt_total 98
telemt_upstream_connect_success_total 96
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 98
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 34
telemt_me_reconnect_success_total 34
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 10086
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33037
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 110
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 34
telemt_me_writer_restored_same_endpoint_total 17
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_user_connections_total{user="hello"} 33029
telemt_user_connections_current{user="hello"} 3066
telemt_user_octets_from_client{user="hello"} 309382660 (295.05 MB)
telemt_user_octets_to_client{user="hello"} 10462868196 (9.74 GB)
telemt_user_unique_ips_current{user="hello"} 1010
telemt_user_unique_ips_recent_window{user="hello"} 418
```