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

# Server Metrics 2026-03-12 19:36:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 43364.9 (12h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216344
telemt_connections_bad_total 2617
telemt_handshake_timeouts_total 4993
telemt_upstream_connect_attempt_total 10988
telemt_upstream_connect_success_total 10938
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 10988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 1431
telemt_me_reconnect_attempts_total 12156
telemt_me_reconnect_success_total 8697
telemt_me_reader_eof_total 9227
telemt_me_idle_close_by_peer_total 9226
telemt_me_route_drop_no_conn_total 65595
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180885
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
telemt_me_writer_removed_unexpected_total 8907
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 8681
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 180843
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 3262224312 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 82895030120 (77.20 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 43258.6 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96543
telemt_connections_bad_total 506
telemt_handshake_timeouts_total 770
telemt_upstream_connect_attempt_total 26399
telemt_upstream_connect_success_total 26117
telemt_upstream_connect_fail_total 282
telemt_upstream_connect_attempts_per_request{bucket="1"} 26399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 463
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 282
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 47205
telemt_me_reconnect_success_total 9149
telemt_me_reader_eof_total 10510
telemt_me_idle_close_by_peer_total 10510
telemt_me_route_drop_no_conn_total 35626
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77007
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
telemt_me_writer_removed_unexpected_total 10410
telemt_me_refill_failed_total 1188
telemt_me_writer_restored_same_endpoint_total 9134
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1261
telemt_user_connections_total{user="hello"} 91773
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 1011997759 (965.12 MB)
telemt_user_octets_to_client{user="hello"} 27090811768 (25.23 GB)
telemt_user_msgs_from_client{user="hello"} 234547
telemt_user_msgs_to_client{user="hello"} 1831829
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 43222.5 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122865
telemt_connections_bad_total 1521
telemt_handshake_timeouts_total 2174
telemt_upstream_connect_attempt_total 11999
telemt_upstream_connect_success_total 11998
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 281
telemt_me_reconnect_attempts_total 10911
telemt_me_reconnect_success_total 9776
telemt_me_reader_eof_total 10382
telemt_me_idle_close_by_peer_total 10382
telemt_me_route_drop_no_conn_total 46050
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114321
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
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 9908
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 9756
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 114293
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 2480242528 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 56160828816 (52.30 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 43197.8 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176709
telemt_connections_bad_total 13151
telemt_handshake_timeouts_total 1262
telemt_upstream_connect_attempt_total 22676
telemt_upstream_connect_success_total 13060
telemt_upstream_connect_fail_total 9616
telemt_upstream_connect_attempts_per_request{bucket="1"} 22676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9616
telemt_me_keepalive_timeout_total 2425
telemt_me_reconnect_attempts_total 39192
telemt_me_reconnect_success_total 8010
telemt_me_reader_eof_total 9230
telemt_me_idle_close_by_peer_total 9223
telemt_me_route_drop_no_conn_total 60829
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141907
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
telemt_me_writer_removed_unexpected_total 9125
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 8000
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1115
telemt_user_connections_total{user="hello"} 144664
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 2629537358 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 57653415229 (53.69 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 43155.0 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274426
telemt_connections_bad_total 2146
telemt_handshake_timeouts_total 2184
telemt_upstream_connect_attempt_total 9049
telemt_upstream_connect_success_total 9003
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 9049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 476
telemt_me_reconnect_attempts_total 10440
telemt_me_reconnect_success_total 6835
telemt_me_reader_eof_total 7288
telemt_me_idle_close_by_peer_total 7287
telemt_me_route_drop_no_conn_total 129023
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273266
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 257
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7035
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6828
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 261575
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 4724508864 (4.40 GB)
telemt_user_octets_to_client{user="hello"} 128890227796 (120.04 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 49
```