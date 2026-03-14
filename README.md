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

# Server Metrics 2026-03-14 18:20:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 18253.5 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104075
telemt_connections_bad_total 15422
telemt_handshake_timeouts_total 595
telemt_upstream_connect_attempt_total 4337
telemt_upstream_connect_success_total 4335
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 3392
telemt_me_reconnect_success_total 3360
telemt_me_reader_eof_total 3554
telemt_me_idle_close_by_peer_total 3554
telemt_me_route_drop_no_conn_total 36295
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83737
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 334
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 213
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3414
telemt_me_writer_restored_same_endpoint_total 3342
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 83665
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 1732783428 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 42415026128 (39.50 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 18252.3 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41676
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 848
telemt_upstream_connect_attempt_total 4948
telemt_upstream_connect_success_total 4912
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 4948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6511
telemt_me_reconnect_success_total 3937
telemt_me_reader_eof_total 4183
telemt_me_idle_close_by_peer_total 4183
telemt_me_route_drop_no_conn_total 22358
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38856
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4075
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 3932
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 38840
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 569257836 (542.89 MB)
telemt_user_octets_to_client{user="hello"} 16643773148 (15.50 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 18256.0 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44632
telemt_connections_bad_total 361
telemt_handshake_timeouts_total 1758
telemt_upstream_connect_attempt_total 6719
telemt_upstream_connect_success_total 6648
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 6719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 103214
telemt_me_reconnect_success_total 5355
telemt_me_reader_eof_total 5716
telemt_me_idle_close_by_peer_total 5716
telemt_me_route_drop_no_conn_total 17689
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40028
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
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5618
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5317
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 40096
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 2901386105 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 23451520154 (21.84 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 18260.7 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56399
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 436
telemt_upstream_connect_attempt_total 4603
telemt_upstream_connect_success_total 4575
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 3630
telemt_me_reconnect_success_total 3609
telemt_me_reader_eof_total 3775
telemt_me_idle_close_by_peer_total 3775
telemt_me_route_drop_no_conn_total 25477
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53465
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 435
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3647
telemt_me_writer_restored_same_endpoint_total 3607
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 53343
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 693310380 (661.19 MB)
telemt_user_octets_to_client{user="hello"} 17099602100 (15.93 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 18254.0 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42295
telemt_connections_bad_total 3543
telemt_handshake_timeouts_total 2231
telemt_upstream_connect_attempt_total 4209
telemt_upstream_connect_success_total 4163
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 4209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 9713
telemt_me_reconnect_success_total 3189
telemt_me_reader_eof_total 3504
telemt_me_idle_close_by_peer_total 3504
telemt_me_route_drop_no_conn_total 14357
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34365
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 200
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3421
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3185
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 34357
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 563274872 (537.18 MB)
telemt_user_octets_to_client{user="hello"} 9274823216 (8.64 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 18253.5 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147420
telemt_connections_bad_total 7167
telemt_handshake_timeouts_total 1876
telemt_upstream_connect_attempt_total 3725
telemt_upstream_connect_success_total 3656
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 3725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1847
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 7679
telemt_me_reconnect_success_total 2681
telemt_me_reader_eof_total 2923
telemt_me_idle_close_by_peer_total 2923
telemt_me_route_drop_no_conn_total 78779
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132976
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
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2864
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2677
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 130817
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 3070263180 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 67686007808 (63.04 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 60
```