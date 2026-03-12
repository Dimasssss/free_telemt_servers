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

# Server Metrics 2026-03-12 10:14:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9693.0 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51237
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 2328
telemt_upstream_connect_attempt_total 2347
telemt_upstream_connect_success_total 2336
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 1835
telemt_me_reconnect_success_total 1822
telemt_me_reader_eof_total 1881
telemt_me_idle_close_by_peer_total 1881
telemt_me_route_drop_no_conn_total 13373
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46211
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 165
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1828
telemt_me_writer_restored_same_endpoint_total 1806
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 46185
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 692666684 (660.58 MB)
telemt_user_octets_to_client{user="hello"} 13028876196 (12.13 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 9586.2 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21024
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 178
telemt_upstream_connect_attempt_total 3524
telemt_upstream_connect_success_total 3455
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 3524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 5742
telemt_me_reconnect_success_total 2948
telemt_me_reader_eof_total 3067
telemt_me_idle_close_by_peer_total 3067
telemt_me_route_drop_no_conn_total 7770
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20054
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 3037
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 2933
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 20052
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 216529024 (206.50 MB)
telemt_user_octets_to_client{user="hello"} 4029794500 (3.75 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 9550.0 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29233
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 214
telemt_upstream_connect_attempt_total 2587
telemt_upstream_connect_success_total 2587
telemt_upstream_connect_attempts_per_request{bucket="1"} 2587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 2084
telemt_me_reconnect_success_total 2071
telemt_me_reader_eof_total 2141
telemt_me_idle_close_by_peer_total 2141
telemt_me_route_drop_no_conn_total 9450
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27192
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2064
telemt_me_writer_restored_same_endpoint_total 2051
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 27185
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 278858984 (265.94 MB)
telemt_user_octets_to_client{user="hello"} 25884232316 (24.11 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 9525.6 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33777
telemt_connections_bad_total 1031
telemt_handshake_timeouts_total 190
telemt_upstream_connect_attempt_total 2724
telemt_upstream_connect_success_total 2657
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 2724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 2176
telemt_me_reconnect_success_total 2140
telemt_me_reader_eof_total 2223
telemt_me_idle_close_by_peer_total 2223
telemt_me_route_drop_no_conn_total 9718
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30150
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 128
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2172
telemt_me_writer_restored_same_endpoint_total 2132
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 30149
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 826009300 (787.74 MB)
telemt_user_octets_to_client{user="hello"} 12781121028 (11.90 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9495.0 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18559
telemt_connections_bad_total 1847
telemt_handshake_timeouts_total 286
telemt_upstream_connect_attempt_total 2888
telemt_upstream_connect_success_total 2781
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 2888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 8682
telemt_me_reconnect_success_total 2268
telemt_me_reader_eof_total 2455
telemt_me_idle_close_by_peer_total 2455
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 5293
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15974
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 279
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 203
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2476
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 2252
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 15971
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 77728552 (74.13 MB)
telemt_user_octets_to_client{user="hello"} 4276383852 (3.98 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 9482.0 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46684
telemt_connections_bad_total 557
telemt_handshake_timeouts_total 609
telemt_upstream_connect_attempt_total 1778
telemt_upstream_connect_success_total 1767
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 1273
telemt_me_reconnect_success_total 1263
telemt_me_reader_eof_total 1323
telemt_me_idle_close_by_peer_total 1323
telemt_me_route_drop_no_conn_total 20531
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43777
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 107
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1279
telemt_me_writer_restored_same_endpoint_total 1256
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 43740
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 1758162596 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 26665594080 (24.83 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 63
```