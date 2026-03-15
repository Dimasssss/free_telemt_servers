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

# Server Metrics 2026-03-15 08:10:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 35749.4 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124974
telemt_connections_bad_total 1013
telemt_handshake_timeouts_total 2925
telemt_upstream_connect_attempt_total 8610
telemt_upstream_connect_success_total 8559
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4711
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 6811
telemt_me_reconnect_success_total 6785
telemt_me_reader_eof_total 7265
telemt_me_idle_close_by_peer_total 7265
telemt_me_route_drop_no_conn_total 231876
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149521
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 921
telemt_desync_full_logged_total 396
telemt_desync_suppressed_total 525
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 383
telemt_desync_frames_bucket_total{bucket="gt_10"} 385
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6847
telemt_me_writer_restored_same_endpoint_total 6754
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 116324
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 1630110976 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 105390457416 (98.15 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 35756.9 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38100
telemt_connections_bad_total 256
telemt_handshake_timeouts_total 1444
telemt_upstream_connect_attempt_total 9540
telemt_upstream_connect_success_total 9540
telemt_upstream_connect_attempts_per_request{bucket="1"} 9540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7785
telemt_me_reconnect_success_total 7751
telemt_me_reader_eof_total 8319
telemt_me_idle_close_by_peer_total 8319
telemt_me_route_drop_no_conn_total 19955
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35025
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7829
telemt_me_writer_restored_same_endpoint_total 7735
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 35028
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 837751900 (798.94 MB)
telemt_user_octets_to_client{user="hello"} 13090480132 (12.19 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 35749.1 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48338
telemt_connections_bad_total 479
telemt_handshake_timeouts_total 1891
telemt_upstream_connect_attempt_total 9501
telemt_upstream_connect_success_total 9500
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7749
telemt_me_reconnect_success_total 7714
telemt_me_reader_eof_total 8329
telemt_me_idle_close_by_peer_total 8329
telemt_me_route_drop_no_conn_total 16440
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43849
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7786
telemt_me_writer_restored_same_endpoint_total 7710
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 43786
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 8904532016 (8.29 GB)
telemt_user_octets_to_client{user="hello"} 25368328996 (23.63 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 35749.0 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57098
telemt_connections_bad_total 156
telemt_handshake_timeouts_total 389
telemt_upstream_connect_attempt_total 8498
telemt_upstream_connect_success_total 8497
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6749
telemt_me_reconnect_success_total 6721
telemt_me_reader_eof_total 7173
telemt_me_idle_close_by_peer_total 7173
telemt_me_route_drop_no_conn_total 24925
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51667
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 98
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6791
telemt_me_writer_restored_same_endpoint_total 6710
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 51601
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 1042334208 (994.05 MB)
telemt_user_octets_to_client{user="hello"} 31686959752 (29.51 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 10820.3 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16892
telemt_connections_bad_total 2084
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 3908
telemt_upstream_connect_success_total 3869
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 3907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 97564
telemt_me_reconnect_success_total 3164
telemt_me_reader_eof_total 3240
telemt_me_idle_close_by_peer_total 3240
telemt_me_route_drop_no_conn_total 4957
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14133
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3113
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 3060
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 14273
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 102291893 (97.55 MB)
telemt_user_octets_to_client{user="hello"} 9491706455 (8.84 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 35748.2 (9h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153310
telemt_connections_bad_total 20106
telemt_handshake_timeouts_total 782
telemt_upstream_connect_attempt_total 7760
telemt_upstream_connect_success_total 7714
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 7760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 5960
telemt_me_reconnect_success_total 5929
telemt_me_reader_eof_total 6314
telemt_me_idle_close_by_peer_total 6314
telemt_me_route_drop_no_conn_total 73081
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128296
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5963
telemt_me_writer_restored_same_endpoint_total 5902
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 126832
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 3500666320 (3.26 GB)
telemt_user_octets_to_client{user="hello"} 68321452460 (63.63 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 55
```