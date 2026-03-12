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

# Server Metrics 2026-03-12 19:41:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 43690.5 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217501
telemt_connections_bad_total 2617
telemt_handshake_timeouts_total 4993
telemt_upstream_connect_attempt_total 11055
telemt_upstream_connect_success_total 11005
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 11055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 1433
telemt_me_reconnect_attempts_total 12223
telemt_me_reconnect_success_total 8764
telemt_me_reader_eof_total 9297
telemt_me_idle_close_by_peer_total 9296
telemt_me_route_drop_no_conn_total 66172
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181778
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
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 8975
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 8748
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 181736
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 3286245640 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 83717111556 (77.97 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 43583.4 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97350
telemt_connections_bad_total 506
telemt_handshake_timeouts_total 771
telemt_upstream_connect_attempt_total 26991
telemt_upstream_connect_success_total 26702
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 26991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 471
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 48585
telemt_me_reconnect_success_total 9153
telemt_me_reader_eof_total 10557
telemt_me_idle_close_by_peer_total 10557
telemt_me_route_drop_no_conn_total 35692
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77221
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 10457
telemt_me_refill_failed_total 1231
telemt_me_writer_restored_same_endpoint_total 9138
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1304
telemt_user_connections_total{user="hello"} 92543
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 1020490756 (973.22 MB)
telemt_user_octets_to_client{user="hello"} 27491828533 (25.60 GB)
telemt_user_msgs_from_client{user="hello"} 242076
telemt_user_msgs_to_client{user="hello"} 1911353
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 43546.9 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123441
telemt_connections_bad_total 1522
telemt_handshake_timeouts_total 2178
telemt_upstream_connect_attempt_total 12116
telemt_upstream_connect_success_total 12115
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6286
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 281
telemt_me_reconnect_attempts_total 10989
telemt_me_reconnect_success_total 9854
telemt_me_reader_eof_total 10473
telemt_me_idle_close_by_peer_total 10473
telemt_me_route_drop_no_conn_total 46323
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114875
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
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9987
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 9834
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 114846
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 2483095732 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 56231714376 (52.37 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 43522.6 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177758
telemt_connections_bad_total 13151
telemt_handshake_timeouts_total 1266
telemt_upstream_connect_attempt_total 22852
telemt_upstream_connect_success_total 13229
telemt_upstream_connect_fail_total 9623
telemt_upstream_connect_attempts_per_request{bucket="1"} 22852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9623
telemt_me_keepalive_timeout_total 2425
telemt_me_reconnect_attempts_total 39318
telemt_me_reconnect_success_total 8136
telemt_me_reader_eof_total 9356
telemt_me_idle_close_by_peer_total 9349
telemt_me_route_drop_no_conn_total 61083
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142642
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 481
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 9251
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 8126
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1115
telemt_user_connections_total{user="hello"} 145399
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 2644444050 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 57853093389 (53.88 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 43479.6 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276175
telemt_connections_bad_total 2146
telemt_handshake_timeouts_total 2189
telemt_upstream_connect_attempt_total 9153
telemt_upstream_connect_success_total 9107
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 9153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 477
telemt_me_reconnect_attempts_total 10501
telemt_me_reconnect_success_total 6895
telemt_me_reader_eof_total 7355
telemt_me_idle_close_by_peer_total 7354
telemt_me_route_drop_no_conn_total 129523
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274987
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 258
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7096
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6888
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 263296
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 4798873840 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 130436621968 (121.48 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 49
```