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

# Server Metrics 2026-03-14 17:44:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 16110.9 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92224
telemt_connections_bad_total 13923
telemt_handshake_timeouts_total 488
telemt_upstream_connect_attempt_total 3838
telemt_upstream_connect_success_total 3836
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 3022
telemt_me_reconnect_success_total 2991
telemt_me_reader_eof_total 3151
telemt_me_idle_close_by_peer_total 3151
telemt_me_route_drop_no_conn_total 33078
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74440
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 310
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3042
telemt_me_writer_restored_same_endpoint_total 2973
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 74369
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 1576935160 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 34841205732 (32.45 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 16109.2 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37688
telemt_connections_bad_total 451
telemt_handshake_timeouts_total 774
telemt_upstream_connect_attempt_total 4435
telemt_upstream_connect_success_total 4401
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 4435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 6130
telemt_me_reconnect_success_total 3557
telemt_me_reader_eof_total 3773
telemt_me_idle_close_by_peer_total 3773
telemt_me_route_drop_no_conn_total 19409
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35110
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3691
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 3552
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 35091
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 474003956 (452.05 MB)
telemt_user_octets_to_client{user="hello"} 14349529624 (13.36 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 16113.7 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39363
telemt_connections_bad_total 352
telemt_handshake_timeouts_total 1706
telemt_upstream_connect_attempt_total 6151
telemt_upstream_connect_success_total 6089
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 6151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 102784
telemt_me_reconnect_success_total 4928
telemt_me_reader_eof_total 5247
telemt_me_idle_close_by_peer_total 5247
telemt_me_route_drop_no_conn_total 15419
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35038
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5187
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 4890
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 35160
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 2825620745 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 17701048318 (16.49 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 16118.6 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50466
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 322
telemt_upstream_connect_attempt_total 4136
telemt_upstream_connect_success_total 4113
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 3298
telemt_me_reconnect_success_total 3277
telemt_me_reader_eof_total 3416
telemt_me_idle_close_by_peer_total 3416
telemt_me_route_drop_no_conn_total 23278
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47854
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 430
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 318
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3313
telemt_me_writer_restored_same_endpoint_total 3275
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 47733
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 588346244 (561.09 MB)
telemt_user_octets_to_client{user="hello"} 15496614464 (14.43 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 16111.5 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36826
telemt_connections_bad_total 3135
telemt_handshake_timeouts_total 1920
telemt_upstream_connect_attempt_total 3720
telemt_upstream_connect_success_total 3678
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 3720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 9357
telemt_me_reconnect_success_total 2835
telemt_me_reader_eof_total 3111
telemt_me_idle_close_by_peer_total 3111
telemt_me_route_drop_no_conn_total 12662
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30119
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 125
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3060
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 2831
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 30113
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 535001148 (510.22 MB)
telemt_user_octets_to_client{user="hello"} 8039653496 (7.49 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 16111.1 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131213
telemt_connections_bad_total 7001
telemt_handshake_timeouts_total 1507
telemt_upstream_connect_attempt_total 3340
telemt_upstream_connect_success_total 3274
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 3340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 7426
telemt_me_reconnect_success_total 2429
telemt_me_reader_eof_total 2649
telemt_me_idle_close_by_peer_total 2649
telemt_me_route_drop_no_conn_total 68135
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117128
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2607
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2425
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 115874
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 2716225284 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 58707545948 (54.68 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 64
```