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

# Server Metrics 2026-03-12 19:20:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 42393.4 (11h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213024
telemt_connections_bad_total 2617
telemt_handshake_timeouts_total 4983
telemt_upstream_connect_attempt_total 10757
telemt_upstream_connect_success_total 10709
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1427
telemt_me_reconnect_attempts_total 11970
telemt_me_reconnect_success_total 8512
telemt_me_reader_eof_total 9021
telemt_me_idle_close_by_peer_total 9020
telemt_me_route_drop_no_conn_total 64068
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178375
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 637
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 396
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 8720
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 8496
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 178333
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 3188528120 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 79985793840 (74.49 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 42286.4 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94551
telemt_connections_bad_total 503
telemt_handshake_timeouts_total 769
telemt_upstream_connect_attempt_total 24558
telemt_upstream_connect_success_total 24283
telemt_upstream_connect_fail_total 275
telemt_upstream_connect_attempts_per_request{bucket="1"} 24558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 275
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 45819
telemt_me_reconnect_success_total 9139
telemt_me_reader_eof_total 10457
telemt_me_idle_close_by_peer_total 10457
telemt_me_route_drop_no_conn_total 35552
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76836
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 11
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
telemt_me_writer_removed_unexpected_total 10357
telemt_me_refill_failed_total 1145
telemt_me_writer_restored_same_endpoint_total 9124
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1218
telemt_user_connections_total{user="hello"} 89839
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 986619397 (940.91 MB)
telemt_user_octets_to_client{user="hello"} 26412222101 (24.60 GB)
telemt_user_msgs_from_client{user="hello"} 206531
telemt_user_msgs_to_client{user="hello"} 1648345
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 42249.9 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121079
telemt_connections_bad_total 1517
telemt_handshake_timeouts_total 2169
telemt_upstream_connect_attempt_total 11771
telemt_upstream_connect_success_total 11770
telemt_upstream_connect_attempts_per_request{bucket="1"} 11770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6103
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 280
telemt_me_reconnect_attempts_total 10730
telemt_me_reconnect_success_total 9595
telemt_me_reader_eof_total 10186
telemt_me_idle_close_by_peer_total 10186
telemt_me_route_drop_no_conn_total 45455
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112592
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
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 9724
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 9575
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 112563
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 2467768744 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 55913254916 (52.07 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 42225.7 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174027
telemt_connections_bad_total 13151
telemt_handshake_timeouts_total 1247
telemt_upstream_connect_attempt_total 22445
telemt_upstream_connect_success_total 12835
telemt_upstream_connect_fail_total 9610
telemt_upstream_connect_attempts_per_request{bucket="1"} 22445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9610
telemt_me_keepalive_timeout_total 2421
telemt_me_reconnect_attempts_total 39010
telemt_me_reconnect_success_total 7829
telemt_me_reader_eof_total 9034
telemt_me_idle_close_by_peer_total 9027
telemt_me_route_drop_no_conn_total 59464
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139539
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
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 8942
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 7819
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1113
telemt_user_connections_total{user="hello"} 142296
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 2609720702 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 57090078953 (53.17 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 42182.3 (11h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268368
telemt_connections_bad_total 2145
telemt_handshake_timeouts_total 2179
telemt_upstream_connect_attempt_total 8893
telemt_upstream_connect_success_total 8847
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 473
telemt_me_reconnect_attempts_total 10327
telemt_me_reconnect_success_total 6722
telemt_me_reader_eof_total 7166
telemt_me_idle_close_by_peer_total 7165
telemt_me_route_drop_no_conn_total 125678
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267020
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 256
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6920
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6715
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 255634
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 4462764368 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 123375614212 (114.90 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 59
```