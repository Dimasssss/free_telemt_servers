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

# Server Metrics 2026-03-12 19:58:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 44664.1 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220987
telemt_connections_bad_total 2617
telemt_handshake_timeouts_total 5001
telemt_upstream_connect_attempt_total 11258
telemt_upstream_connect_success_total 11207
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 11258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1438
telemt_me_reconnect_attempts_total 12382
telemt_me_reconnect_success_total 8922
telemt_me_reader_eof_total 9466
telemt_me_idle_close_by_peer_total 9465
telemt_me_route_drop_no_conn_total 67009
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184482
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 642
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 401
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9134
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 8906
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 184440
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 3415670420 (3.18 GB)
telemt_user_octets_to_client{user="hello"} 86029404364 (80.12 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 44557.1 (12h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99467
telemt_connections_bad_total 532
telemt_handshake_timeouts_total 777
telemt_upstream_connect_attempt_total 28319
telemt_upstream_connect_success_total 28029
telemt_upstream_connect_fail_total 290
telemt_upstream_connect_attempts_per_request{bucket="1"} 28319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8091
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 484
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 290
telemt_me_keepalive_timeout_total 337
telemt_me_reconnect_attempts_total 48688
telemt_me_reconnect_success_total 9256
telemt_me_reader_eof_total 10662
telemt_me_idle_close_by_peer_total 10662
telemt_me_route_drop_no_conn_total 36200
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77970
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
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 10561
telemt_me_refill_failed_total 1231
telemt_me_writer_restored_same_endpoint_total 9241
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1305
telemt_user_connections_total{user="hello"} 94473
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 1032898160 (985.05 MB)
telemt_user_octets_to_client{user="hello"} 27830921823 (25.92 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 44520.6 (12h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124864
telemt_connections_bad_total 1523
telemt_handshake_timeouts_total 2186
telemt_upstream_connect_attempt_total 12381
telemt_upstream_connect_success_total 12380
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 285
telemt_me_reconnect_attempts_total 11211
telemt_me_reconnect_success_total 10075
telemt_me_reader_eof_total 10712
telemt_me_idle_close_by_peer_total 10712
telemt_me_route_drop_no_conn_total 47029
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116252
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
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 10210
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 10055
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 116224
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 2488946052 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 56374046244 (52.50 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 44496.3 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180576
telemt_connections_bad_total 13151
telemt_handshake_timeouts_total 1272
telemt_upstream_connect_attempt_total 23154
telemt_upstream_connect_success_total 13526
telemt_upstream_connect_fail_total 9628
telemt_upstream_connect_attempts_per_request{bucket="1"} 23154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9628
telemt_me_keepalive_timeout_total 2430
telemt_me_reconnect_attempts_total 39572
telemt_me_reconnect_success_total 8390
telemt_me_reader_eof_total 9635
telemt_me_idle_close_by_peer_total 9628
telemt_me_route_drop_no_conn_total 61993
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145287
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 482
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 9507
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 8380
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1117
telemt_user_connections_total{user="hello"} 148043
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 2704531602 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 58487316913 (54.47 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 44452.8 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280661
telemt_connections_bad_total 2148
telemt_handshake_timeouts_total 2193
telemt_upstream_connect_attempt_total 9355
telemt_upstream_connect_success_total 9307
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 9354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 483
telemt_me_reconnect_attempts_total 10659
telemt_me_reconnect_success_total 7052
telemt_me_reader_eof_total 7523
telemt_me_idle_close_by_peer_total 7522
telemt_me_route_drop_no_conn_total 130964
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279409
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
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7254
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 7045
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 267718
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 4961810216 (4.62 GB)
telemt_user_octets_to_client{user="hello"} 134669882576 (125.42 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 37
```