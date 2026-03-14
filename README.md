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

# Server Metrics 2026-03-14 21:55:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 31124.7 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145953
telemt_connections_bad_total 16437
telemt_handshake_timeouts_total 1562
telemt_upstream_connect_attempt_total 7045
telemt_upstream_connect_success_total 7043
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 5494
telemt_me_reconnect_success_total 5454
telemt_me_reader_eof_total 5799
telemt_me_idle_close_by_peer_total 5799
telemt_me_route_drop_no_conn_total 52854
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121414
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 583
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5541
telemt_me_writer_restored_same_endpoint_total 5436
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 121334
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 2595441992 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 74021171596 (68.94 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 31122.9 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60498
telemt_connections_bad_total 738
telemt_handshake_timeouts_total 999
telemt_upstream_connect_attempt_total 8092
telemt_upstream_connect_success_total 8040
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 8092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 146
telemt_me_reconnect_attempts_total 9033
telemt_me_reconnect_success_total 6450
telemt_me_reader_eof_total 6873
telemt_me_idle_close_by_peer_total 6873
telemt_me_route_drop_no_conn_total 32535
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56493
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6617
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 6445
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 56414
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 1397145844 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 26340695580 (24.53 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 31127.8 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68702
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 1917
telemt_upstream_connect_attempt_total 10190
telemt_upstream_connect_success_total 10086
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 10190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 106046
telemt_me_reconnect_success_total 8181
telemt_me_reader_eof_total 8746
telemt_me_idle_close_by_peer_total 8746
telemt_me_route_drop_no_conn_total 25438
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62949
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 8466
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 8135
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 63012
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 3972223381 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 50081788402 (46.64 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 31132.1 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86334
telemt_connections_bad_total 213
telemt_handshake_timeouts_total 619
telemt_upstream_connect_attempt_total 7605
telemt_upstream_connect_success_total 7560
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 7605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 211
telemt_me_reconnect_attempts_total 5836
telemt_me_reconnect_success_total 5806
telemt_me_reader_eof_total 6127
telemt_me_idle_close_by_peer_total 6127
telemt_me_route_drop_no_conn_total 37644
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81864
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 663
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 5869
telemt_me_writer_restored_same_endpoint_total 5804
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 81908
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 1358337820 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 29735220042 (27.69 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 31125.3 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65442
telemt_connections_bad_total 6058
telemt_handshake_timeouts_total 3389
telemt_upstream_connect_attempt_total 7615
telemt_upstream_connect_success_total 7528
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 7615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 12475
telemt_me_reconnect_success_total 5935
telemt_me_reader_eof_total 6426
telemt_me_idle_close_by_peer_total 6426
telemt_me_route_drop_no_conn_total 21017
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52744
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 270
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6195
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 5931
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 52730
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 1414614232 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 32114114540 (29.91 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 31124.9 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220480
telemt_connections_bad_total 7767
telemt_handshake_timeouts_total 2719
telemt_upstream_connect_attempt_total 6218
telemt_upstream_connect_success_total 6105
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 6218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 9527
telemt_me_reconnect_success_total 4517
telemt_me_reader_eof_total 4886
telemt_me_idle_close_by_peer_total 4886
telemt_me_route_drop_no_conn_total 123334
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203600
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4729
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 4513
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 200083
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 6320772008 (5.89 GB)
telemt_user_octets_to_client{user="hello"} 109694727376 (102.16 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 33
```