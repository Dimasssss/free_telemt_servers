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

# Server Metrics 2026-03-12 23:11:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 56314.8 (15h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248806
telemt_connections_bad_total 2720
telemt_handshake_timeouts_total 5254
telemt_upstream_connect_attempt_total 14161
telemt_upstream_connect_success_total 14099
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 14161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1480
telemt_me_reconnect_attempts_total 14715
telemt_me_reconnect_success_total 11245
telemt_me_reader_eof_total 11980
telemt_me_idle_close_by_peer_total 11979
telemt_me_route_drop_no_conn_total 77029
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205179
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 687
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 433
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11479
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 11229
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 204945
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 3819828768 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 104719769964 (97.53 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 56208.1 (15h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113096
telemt_connections_bad_total 569
telemt_handshake_timeouts_total 836
telemt_upstream_connect_attempt_total 32801
telemt_upstream_connect_success_total 32434
telemt_upstream_connect_fail_total 367
telemt_upstream_connect_attempts_per_request{bucket="1"} 32801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 367
telemt_me_keepalive_timeout_total 404
telemt_me_reconnect_attempts_total 54965
telemt_me_reconnect_success_total 13095
telemt_me_reader_eof_total 14727
telemt_me_idle_close_by_peer_total 14727
telemt_me_route_drop_no_conn_total 41119
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90980
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 14497
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 13080
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1402
telemt_user_connections_total{user="hello"} 107482
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 1200693856 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 33881969203 (31.56 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 56171.7 (15h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138551
telemt_connections_bad_total 1607
telemt_handshake_timeouts_total 2223
telemt_upstream_connect_attempt_total 15464
telemt_upstream_connect_success_total 15463
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8169
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 13730
telemt_me_reconnect_success_total 12583
telemt_me_reader_eof_total 13427
telemt_me_idle_close_by_peer_total 13427
telemt_me_route_drop_no_conn_total 52108
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 129495
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12740
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 12563
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 129461
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 2582619424 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 60511396508 (56.36 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 56147.3 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202280
telemt_connections_bad_total 13261
telemt_handshake_timeouts_total 1372
telemt_upstream_connect_attempt_total 26933
telemt_upstream_connect_success_total 17233
telemt_upstream_connect_fail_total 9700
telemt_upstream_connect_attempts_per_request{bucket="1"} 26933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7944
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9700
telemt_me_keepalive_timeout_total 2493
telemt_me_reconnect_attempts_total 43775
telemt_me_reconnect_success_total 11528
telemt_me_reader_eof_total 12963
telemt_me_idle_close_by_peer_total 12956
telemt_me_route_drop_no_conn_total 71223
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166341
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12709
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 11518
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1181
telemt_user_connections_total{user="hello"} 169095
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 2980801806 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 68665888153 (63.95 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 6318.9 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6034
telemt_connections_bad_total 1162
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 1820
telemt_upstream_connect_success_total 1801
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1475
telemt_me_reconnect_success_total 1474
telemt_me_reader_eof_total 1557
telemt_me_idle_close_by_peer_total 1557
telemt_me_route_drop_no_conn_total 1622
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4663
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1481
telemt_me_writer_restored_same_endpoint_total 1458
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 4663
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 12970404 (12.37 MB)
telemt_user_octets_to_client{user="hello"} 1322740060 (1.23 GB)
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 56103.7 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330307
telemt_connections_bad_total 5143
telemt_handshake_timeouts_total 2513
telemt_upstream_connect_attempt_total 11797
telemt_upstream_connect_success_total 11731
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 11797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 507
telemt_me_reconnect_attempts_total 12521
telemt_me_reconnect_success_total 8908
telemt_me_reader_eof_total 9526
telemt_me_idle_close_by_peer_total 9525
telemt_me_route_drop_no_conn_total 148816
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324687
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9128
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 8901
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 312989
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 5472173776 (5.10 GB)
telemt_user_octets_to_client{user="hello"} 167103857048 (155.63 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 27
```