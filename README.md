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

# Server Metrics 2026-03-14 14:46:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 5381.6 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31839
telemt_connections_bad_total 5971
telemt_handshake_timeouts_total 164
telemt_upstream_connect_attempt_total 1319
telemt_upstream_connect_success_total 1319
telemt_upstream_connect_attempts_per_request{bucket="1"} 1319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1029
telemt_me_reconnect_success_total 1015
telemt_me_reader_eof_total 1037
telemt_me_idle_close_by_peer_total 1037
telemt_me_route_drop_no_conn_total 12317
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25132
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1036
telemt_me_writer_restored_same_endpoint_total 997
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 25072
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 405936184 (387.13 MB)
telemt_user_octets_to_client{user="hello"} 9433379272 (8.79 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 5379.7 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12676
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 480
telemt_upstream_connect_attempt_total 1527
telemt_upstream_connect_success_total 1503
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 1229
telemt_me_reconnect_success_total 1202
telemt_me_reader_eof_total 1225
telemt_me_idle_close_by_peer_total 1225
telemt_me_route_drop_no_conn_total 6748
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11748
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1223
telemt_me_writer_restored_same_endpoint_total 1197
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 11731
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 125141388 (119.34 MB)
telemt_user_octets_to_client{user="hello"} 3345992196 (3.12 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 5384.0 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11963
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 216
telemt_upstream_connect_attempt_total 2756
telemt_upstream_connect_success_total 2736
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 2756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 95994
telemt_me_reconnect_success_total 2120
telemt_me_reader_eof_total 2219
telemt_me_idle_close_by_peer_total 2219
telemt_me_route_drop_no_conn_total 4702
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10663
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 2236
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 2082
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 10969
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 453834505 (432.81 MB)
telemt_user_octets_to_client{user="hello"} 5186509210 (4.83 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 5389.2 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16804
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 138
telemt_upstream_connect_attempt_total 1411
telemt_upstream_connect_success_total 1405
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 1116
telemt_me_reconnect_success_total 1109
telemt_me_reader_eof_total 1110
telemt_me_idle_close_by_peer_total 1110
telemt_me_route_drop_no_conn_total 8533
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15954
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 208
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1109
telemt_me_writer_restored_same_endpoint_total 1107
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_user_connections_total{user="hello"} 15836
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 194567284 (185.55 MB)
telemt_user_octets_to_client{user="hello"} 5633773180 (5.25 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 5382.1 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12348
telemt_connections_bad_total 1147
telemt_handshake_timeouts_total 143
telemt_upstream_connect_attempt_total 1322
telemt_upstream_connect_success_total 1303
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 756
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 4819
telemt_me_reconnect_success_total 1003
telemt_me_reader_eof_total 1097
telemt_me_idle_close_by_peer_total 1097
telemt_me_route_drop_no_conn_total 4186
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10329
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 58
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 1117
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 999
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 10325
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 85037092 (81.10 MB)
telemt_user_octets_to_client{user="hello"} 2568580220 (2.39 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 5381.7 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43003
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 337
telemt_upstream_connect_attempt_total 1172
telemt_upstream_connect_success_total 1142
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 1172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 866
telemt_me_reconnect_success_total 840
telemt_me_reader_eof_total 842
telemt_me_idle_close_by_peer_total 842
telemt_me_route_drop_no_conn_total 21554
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39476
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 839
telemt_me_writer_restored_same_endpoint_total 836
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 39387
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 728173780 (694.44 MB)
telemt_user_octets_to_client{user="hello"} 14765064684 (13.75 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 87
```