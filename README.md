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

# Server Metrics 2026-03-16 18:43:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 18313.7 (5h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177944
telemt_connections_bad_total 902
telemt_handshake_timeouts_total 4479
telemt_upstream_connect_attempt_total 3825
telemt_upstream_connect_success_total 3810
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4006
telemt_me_reconnect_success_total 2835
telemt_me_reader_eof_total 2957
telemt_me_idle_close_by_peer_total 2956
telemt_me_route_drop_no_conn_total 56059
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166732
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 858
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 655
telemt_desync_frames_bucket_total{bucket="1_2"} 317
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2896
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2833
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 166645
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 3322005796 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 95412680816 (88.86 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 118.1 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1583
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 96
telemt_upstream_connect_success_total 93
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 96
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 27
telemt_me_reconnect_success_total 27
telemt_me_route_drop_no_conn_total 611
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1489
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 11
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_user_connections_total{user="hello"} 1490
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 7193652 (6.86 MB)
telemt_user_octets_to_client{user="hello"} 216851744 (206.81 MB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 18427.1 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73479
telemt_connections_bad_total 94
telemt_handshake_timeouts_total 921
telemt_upstream_connect_attempt_total 5291
telemt_upstream_connect_success_total 5236
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 5291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 42163
telemt_me_reconnect_success_total 3275
telemt_me_reader_eof_total 3658
telemt_me_idle_close_by_peer_total 3658
telemt_me_route_drop_no_conn_total 26104
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68137
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 172
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3615
telemt_me_refill_failed_total 1214
telemt_me_writer_restored_same_endpoint_total 3231
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 340
telemt_user_connections_total{user="hello"} 69069
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 929051370 (886.01 MB)
telemt_user_octets_to_client{user="hello"} 20234510602 (18.84 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

Не удалось получить метрики для этого сервера.

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 16024.5 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79693
telemt_connections_bad_total 21180
telemt_handshake_timeouts_total 594
telemt_upstream_connect_attempt_total 4237
telemt_upstream_connect_success_total 4176
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 4237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 5008
telemt_me_reconnect_success_total 3343
telemt_me_reader_eof_total 3475
telemt_me_idle_close_by_peer_total 3475
telemt_me_route_drop_no_conn_total 53422
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74047
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 73
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3503
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 3343
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 55086
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 2123589372 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 35785831652 (33.33 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 87.2 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1755
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 85
telemt_upstream_connect_success_total 83
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 85
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 18
telemt_me_reconnect_success_total 18
telemt_me_route_drop_no_conn_total 309
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1643
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 1643
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 10232108 (9.76 MB)
telemt_user_octets_to_client{user="hello"} 282429508 (269.35 MB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 87
```