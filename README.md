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

# Server Metrics 2026-03-14 17:49:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 16416.2 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94059
telemt_connections_bad_total 14107
telemt_handshake_timeouts_total 492
telemt_upstream_connect_attempt_total 3940
telemt_upstream_connect_success_total 3938
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 3081
telemt_me_reconnect_success_total 3050
telemt_me_reader_eof_total 3221
telemt_me_idle_close_by_peer_total 3221
telemt_me_route_drop_no_conn_total 33630
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75935
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3101
telemt_me_writer_restored_same_endpoint_total 3032
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 75864
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 1601430268 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 35572237556 (33.13 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 16414.6 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38254
telemt_connections_bad_total 451
telemt_handshake_timeouts_total 815
telemt_upstream_connect_attempt_total 4535
telemt_upstream_connect_success_total 4500
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 6186
telemt_me_reconnect_success_total 3613
telemt_me_reader_eof_total 3837
telemt_me_idle_close_by_peer_total 3837
telemt_me_route_drop_no_conn_total 20119
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35610
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3747
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 3608
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 35595
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 480340380 (458.09 MB)
telemt_user_octets_to_client{user="hello"} 15074464580 (14.04 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 16419.0 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40103
telemt_connections_bad_total 355
telemt_handshake_timeouts_total 1712
telemt_upstream_connect_attempt_total 6261
telemt_upstream_connect_success_total 6195
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 6261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 102847
telemt_me_reconnect_success_total 4990
telemt_me_reader_eof_total 5323
telemt_me_idle_close_by_peer_total 5323
telemt_me_route_drop_no_conn_total 15668
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35720
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
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 5250
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 4952
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 35833
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 2841923701 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 18302675490 (17.05 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 16423.4 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51074
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 324
telemt_upstream_connect_attempt_total 4237
telemt_upstream_connect_success_total 4212
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 4237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 3354
telemt_me_reconnect_success_total 3334
telemt_me_reader_eof_total 3480
telemt_me_idle_close_by_peer_total 3480
telemt_me_route_drop_no_conn_total 23578
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48435
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 432
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3369
telemt_me_writer_restored_same_endpoint_total 3332
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 48314
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 600854932 (573.02 MB)
telemt_user_octets_to_client{user="hello"} 15965114768 (14.87 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 16416.6 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37643
telemt_connections_bad_total 3193
telemt_handshake_timeouts_total 1922
telemt_upstream_connect_attempt_total 3833
telemt_upstream_connect_success_total 3789
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 3833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 9425
telemt_me_reconnect_success_total 2903
telemt_me_reader_eof_total 3196
telemt_me_idle_close_by_peer_total 3196
telemt_me_route_drop_no_conn_total 12967
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30831
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 3128
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 2899
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 30824
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 544043468 (518.84 MB)
telemt_user_octets_to_client{user="hello"} 8125259048 (7.57 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 16416.0 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133743
telemt_connections_bad_total 7028
telemt_handshake_timeouts_total 1569
telemt_upstream_connect_attempt_total 3425
telemt_upstream_connect_success_total 3358
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 3425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1703
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 7467
telemt_me_reconnect_success_total 2470
telemt_me_reader_eof_total 2696
telemt_me_idle_close_by_peer_total 2696
telemt_me_route_drop_no_conn_total 69581
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119465
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
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2648
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2466
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 118123
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 2824357000 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 60282017436 (56.14 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 68
```