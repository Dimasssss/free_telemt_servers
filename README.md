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

# Server Metrics 2026-03-14 19:11:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 21320.3 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116090
telemt_connections_bad_total 15720
telemt_handshake_timeouts_total 1067
telemt_upstream_connect_attempt_total 4953
telemt_upstream_connect_success_total 4951
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 183
telemt_me_reconnect_attempts_total 3879
telemt_me_reconnect_success_total 3846
telemt_me_reader_eof_total 4071
telemt_me_idle_close_by_peer_total 4071
telemt_me_route_drop_no_conn_total 40807
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94344
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 374
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3906
telemt_me_writer_restored_same_endpoint_total 3828
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 94272
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 1872308144 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 46427558504 (43.24 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 21318.2 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47265
telemt_connections_bad_total 584
telemt_handshake_timeouts_total 874
telemt_upstream_connect_attempt_total 5613
telemt_upstream_connect_success_total 5574
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 5613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 7044
telemt_me_reconnect_success_total 4470
telemt_me_reader_eof_total 4749
telemt_me_idle_close_by_peer_total 4749
telemt_me_route_drop_no_conn_total 25033
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44092
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4613
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4465
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 44075
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 637144528 (607.63 MB)
telemt_user_octets_to_client{user="hello"} 18685844344 (17.40 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 21322.8 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51147
telemt_connections_bad_total 385
telemt_handshake_timeouts_total 1820
telemt_upstream_connect_attempt_total 7463
telemt_upstream_connect_success_total 7384
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 7463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 180
telemt_me_reconnect_attempts_total 103821
telemt_me_reconnect_success_total 5958
telemt_me_reader_eof_total 6357
telemt_me_idle_close_by_peer_total 6357
telemt_me_route_drop_no_conn_total 20084
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46146
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 8
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
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 6224
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5917
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 46210
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 3105201833 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 26365395710 (24.55 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 21327.5 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65347
telemt_connections_bad_total 179
telemt_handshake_timeouts_total 549
telemt_upstream_connect_attempt_total 5228
telemt_upstream_connect_success_total 5196
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2812
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 4121
telemt_me_reconnect_success_total 4099
telemt_me_reader_eof_total 4295
telemt_me_idle_close_by_peer_total 4295
telemt_me_route_drop_no_conn_total 28895
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61745
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 533
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4141
telemt_me_writer_restored_same_endpoint_total 4097
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 61621
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 860767816 (820.89 MB)
telemt_user_octets_to_client{user="hello"} 19581001744 (18.24 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 21320.6 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48887
telemt_connections_bad_total 4121
telemt_handshake_timeouts_total 3117
telemt_upstream_connect_attempt_total 4911
telemt_upstream_connect_success_total 4855
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 4911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 10276
telemt_me_reconnect_success_total 3749
telemt_me_reader_eof_total 4099
telemt_me_idle_close_by_peer_total 4099
telemt_me_route_drop_no_conn_total 16684
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39343
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 239
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 204
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3988
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3745
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 39332
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 609046052 (580.83 MB)
telemt_user_octets_to_client{user="hello"} 11654695568 (10.85 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 21320.0 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170131
telemt_connections_bad_total 7209
telemt_handshake_timeouts_total 2581
telemt_upstream_connect_attempt_total 4196
telemt_upstream_connect_success_total 4123
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 4196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 8017
telemt_me_reconnect_success_total 3017
telemt_me_reader_eof_total 3284
telemt_me_idle_close_by_peer_total 3284
telemt_me_route_drop_no_conn_total 91779
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154964
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3206
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3013
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 151836
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 3367331612 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 77560250412 (72.23 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 74
```