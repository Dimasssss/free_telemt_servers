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

# Server Metrics 2026-03-14 18:30:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 18866.6 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106786
telemt_connections_bad_total 15518
telemt_handshake_timeouts_total 776
telemt_upstream_connect_attempt_total 4423
telemt_upstream_connect_success_total 4421
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 3478
telemt_me_reconnect_success_total 3446
telemt_me_reader_eof_total 3640
telemt_me_idle_close_by_peer_total 3640
telemt_me_route_drop_no_conn_total 37438
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86019
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3500
telemt_me_writer_restored_same_endpoint_total 3428
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 85947
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 1769500064 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 43191000004 (40.22 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 18865.0 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42842
telemt_connections_bad_total 501
telemt_handshake_timeouts_total 860
telemt_upstream_connect_attempt_total 5050
telemt_upstream_connect_success_total 5014
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 5050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 6613
telemt_me_reconnect_success_total 4039
telemt_me_reader_eof_total 4285
telemt_me_idle_close_by_peer_total 4285
telemt_me_route_drop_no_conn_total 23053
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39930
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
telemt_me_writer_removed_unexpected_total 4178
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 4034
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 39914
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 577830628 (551.06 MB)
telemt_user_octets_to_client{user="hello"} 17257155540 (16.07 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 18869.2 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45972
telemt_connections_bad_total 372
telemt_handshake_timeouts_total 1768
telemt_upstream_connect_attempt_total 6829
telemt_upstream_connect_success_total 6758
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 6829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 103324
telemt_me_reconnect_success_total 5464
telemt_me_reader_eof_total 5825
telemt_me_idle_close_by_peer_total 5825
telemt_me_route_drop_no_conn_total 18115
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41300
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
telemt_me_writer_removed_unexpected_total 5727
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 5426
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 41365
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 2913456149 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 24057052034 (22.40 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 18874.0 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58215
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 470
telemt_upstream_connect_attempt_total 4666
telemt_upstream_connect_success_total 4638
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 3693
telemt_me_reconnect_success_total 3672
telemt_me_reader_eof_total 3840
telemt_me_idle_close_by_peer_total 3840
telemt_me_route_drop_no_conn_total 26171
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55108
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 462
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 342
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 190
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3712
telemt_me_writer_restored_same_endpoint_total 3670
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 54986
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 768222088 (732.63 MB)
telemt_user_octets_to_client{user="hello"} 17466167288 (16.27 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 18867.0 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43905
telemt_connections_bad_total 3653
telemt_handshake_timeouts_total 2523
telemt_upstream_connect_attempt_total 4311
telemt_upstream_connect_success_total 4265
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 4311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 9815
telemt_me_reconnect_success_total 3290
telemt_me_reader_eof_total 3607
telemt_me_idle_close_by_peer_total 3607
telemt_me_route_drop_no_conn_total 14960
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35545
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 202
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3524
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3286
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 35537
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 574125136 (547.53 MB)
telemt_user_octets_to_client{user="hello"} 9716138396 (9.05 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 18866.6 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151802
telemt_connections_bad_total 7174
telemt_handshake_timeouts_total 2116
telemt_upstream_connect_attempt_total 3789
telemt_upstream_connect_success_total 3720
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 3789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1884
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 7743
telemt_me_reconnect_success_total 2745
telemt_me_reader_eof_total 2987
telemt_me_idle_close_by_peer_total 2987
telemt_me_route_drop_no_conn_total 81485
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137159
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
telemt_me_writer_removed_unexpected_total 2928
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2741
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 134717
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 3138986636 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 70200802696 (65.38 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 83
```