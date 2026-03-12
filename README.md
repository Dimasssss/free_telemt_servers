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

# Server Metrics 2026-03-12 20:25:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 46286.9 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227307
telemt_connections_bad_total 2625
telemt_handshake_timeouts_total 5038
telemt_upstream_connect_attempt_total 11614
telemt_upstream_connect_success_total 11561
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 11614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1446
telemt_me_reconnect_attempts_total 12650
telemt_me_reconnect_success_total 9189
telemt_me_reader_eof_total 9758
telemt_me_idle_close_by_peer_total 9757
telemt_me_route_drop_no_conn_total 69472
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189273
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 9405
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 9173
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 189050
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 3613761088 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 91237480428 (84.97 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 46179.9 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102105
telemt_connections_bad_total 535
telemt_handshake_timeouts_total 788
telemt_upstream_connect_attempt_total 28871
telemt_upstream_connect_success_total 28575
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 28871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8411
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 490
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 348
telemt_me_reconnect_attempts_total 49147
telemt_me_reconnect_success_total 9715
telemt_me_reader_eof_total 11144
telemt_me_idle_close_by_peer_total 11144
telemt_me_route_drop_no_conn_total 37071
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80526
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 12
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
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 11021
telemt_me_refill_failed_total 1231
telemt_me_writer_restored_same_endpoint_total 9700
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1306
telemt_user_connections_total{user="hello"} 97029
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 1053329032 (1004.53 MB)
telemt_user_octets_to_client{user="hello"} 28316186947 (26.37 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 46143.2 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127256
telemt_connections_bad_total 1535
telemt_handshake_timeouts_total 2189
telemt_upstream_connect_attempt_total 12820
telemt_upstream_connect_success_total 12819
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 292
telemt_me_reconnect_attempts_total 11564
telemt_me_reconnect_success_total 10427
telemt_me_reader_eof_total 11098
telemt_me_idle_close_by_peer_total 11098
telemt_me_route_drop_no_conn_total 48155
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118571
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10565
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 10407
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 118541
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 2502045376 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 57036162072 (53.12 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 46119.2 (12h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185152
telemt_connections_bad_total 13156
telemt_handshake_timeouts_total 1277
telemt_upstream_connect_attempt_total 23634
telemt_upstream_connect_success_total 13989
telemt_upstream_connect_fail_total 9645
telemt_upstream_connect_attempts_per_request{bucket="1"} 23634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9645
telemt_me_keepalive_timeout_total 2438
telemt_me_reconnect_attempts_total 39949
telemt_me_reconnect_success_total 8766
telemt_me_reader_eof_total 10017
telemt_me_idle_close_by_peer_total 10010
telemt_me_route_drop_no_conn_total 63699
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149727
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 491
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 9889
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 8756
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1123
telemt_user_connections_total{user="hello"} 152482
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 2859243734 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 59956772121 (55.84 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 46075.5 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289131
telemt_connections_bad_total 2441
telemt_handshake_timeouts_total 2214
telemt_upstream_connect_attempt_total 9689
telemt_upstream_connect_success_total 9639
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 485
telemt_me_reconnect_attempts_total 10902
telemt_me_reconnect_success_total 7295
telemt_me_reader_eof_total 7783
telemt_me_idle_close_by_peer_total 7782
telemt_me_route_drop_no_conn_total 133984
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287361
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 274
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 169
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7499
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 7288
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 275669
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 5036547976 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 136639116256 (127.26 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 44
```