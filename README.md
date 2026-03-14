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

# Server Metrics 2026-03-14 21:34:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 29899.2 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143460
telemt_connections_bad_total 16368
telemt_handshake_timeouts_total 1522
telemt_upstream_connect_attempt_total 6764
telemt_upstream_connect_success_total 6762
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 5256
telemt_me_reconnect_success_total 5218
telemt_me_reader_eof_total 5548
telemt_me_idle_close_by_peer_total 5548
telemt_me_route_drop_no_conn_total 52067
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119081
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 570
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 373
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5302
telemt_me_writer_restored_same_endpoint_total 5200
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 119001
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 2517198060 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 72537253432 (67.56 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 29897.5 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59464
telemt_connections_bad_total 735
telemt_handshake_timeouts_total 997
telemt_upstream_connect_attempt_total 7769
telemt_upstream_connect_success_total 7719
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 7769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 8755
telemt_me_reconnect_success_total 6174
telemt_me_reader_eof_total 6577
telemt_me_idle_close_by_peer_total 6577
telemt_me_route_drop_no_conn_total 32247
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55500
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
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6336
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 6169
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 55421
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 1384860332 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 25156621396 (23.43 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 29901.9 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67102
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 1912
telemt_upstream_connect_attempt_total 9866
telemt_upstream_connect_success_total 9764
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 9866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5205
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 105767
telemt_me_reconnect_success_total 7902
telemt_me_reader_eof_total 8449
telemt_me_idle_close_by_peer_total 8449
telemt_me_route_drop_no_conn_total 24946
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61398
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 8185
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 7856
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 61461
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 3934059429 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 47682197886 (44.41 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 29906.6 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84955
telemt_connections_bad_total 213
telemt_handshake_timeouts_total 619
telemt_upstream_connect_attempt_total 7320
telemt_upstream_connect_success_total 7276
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 7320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 5596
telemt_me_reconnect_success_total 5566
telemt_me_reader_eof_total 5875
telemt_me_idle_close_by_peer_total 5875
telemt_me_route_drop_no_conn_total 36748
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80522
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 658
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 489
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 276
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5627
telemt_me_writer_restored_same_endpoint_total 5564
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 80566
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 1336255560 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 28924580274 (26.94 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 29899.9 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64101
telemt_connections_bad_total 5838
telemt_handshake_timeouts_total 3382
telemt_upstream_connect_attempt_total 7298
telemt_upstream_connect_success_total 7213
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 7298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 222
telemt_me_reconnect_attempts_total 12203
telemt_me_reconnect_success_total 5665
telemt_me_reader_eof_total 6139
telemt_me_idle_close_by_peer_total 6139
telemt_me_route_drop_no_conn_total 20638
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51679
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
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5922
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 5661
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 51665
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 1409681644 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 31941909280 (29.75 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 29899.2 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215974
telemt_connections_bad_total 7665
telemt_handshake_timeouts_total 2693
telemt_upstream_connect_attempt_total 5981
telemt_upstream_connect_success_total 5872
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 5981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 261
telemt_me_reconnect_attempts_total 9337
telemt_me_reconnect_success_total 4328
telemt_me_reader_eof_total 4688
telemt_me_idle_close_by_peer_total 4688
telemt_me_route_drop_no_conn_total 120284
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199319
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 115
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4538
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 4324
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 195803
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 5188675536 (4.83 GB)
telemt_user_octets_to_client{user="hello"} 107950737460 (100.54 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 37
```