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

# Server Metrics 2026-03-14 17:09:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 13963.4 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79169
telemt_connections_bad_total 12384
telemt_handshake_timeouts_total 351
telemt_upstream_connect_attempt_total 3402
telemt_upstream_connect_success_total 3400
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 2673
telemt_me_reconnect_success_total 2644
telemt_me_reader_eof_total 2785
telemt_me_idle_close_by_peer_total 2785
telemt_me_route_drop_no_conn_total 28877
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64100
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 265
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2694
telemt_me_writer_restored_same_endpoint_total 2626
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 64030
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 1326468244 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 30465938224 (28.37 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 13961.6 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33253
telemt_connections_bad_total 399
telemt_handshake_timeouts_total 696
telemt_upstream_connect_attempt_total 4012
telemt_upstream_connect_success_total 3980
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 4012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 5795
telemt_me_reconnect_success_total 3223
telemt_me_reader_eof_total 3415
telemt_me_idle_close_by_peer_total 3415
telemt_me_route_drop_no_conn_total 16797
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30986
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3350
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 3218
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 30968
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 381992660 (364.30 MB)
telemt_user_octets_to_client{user="hello"} 12126057360 (11.29 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 13966.0 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33441
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 1660
telemt_upstream_connect_attempt_total 5641
telemt_upstream_connect_success_total 5587
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 5641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 102368
telemt_me_reconnect_success_total 4515
telemt_me_reader_eof_total 4801
telemt_me_idle_close_by_peer_total 4801
telemt_me_route_drop_no_conn_total 12508
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29354
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
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 4769
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 4477
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 29636
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 2775041757 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 15666494030 (14.59 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 13970.7 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43331
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 272
telemt_upstream_connect_attempt_total 3734
telemt_upstream_connect_success_total 3717
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 2989
telemt_me_reconnect_success_total 2971
telemt_me_reader_eof_total 3088
telemt_me_idle_close_by_peer_total 3088
telemt_me_route_drop_no_conn_total 20775
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41180
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 388
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2999
telemt_me_writer_restored_same_endpoint_total 2969
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 41059
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 453622808 (432.61 MB)
telemt_user_octets_to_client{user="hello"} 13699341788 (12.76 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 13963.8 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30779
telemt_connections_bad_total 2740
telemt_handshake_timeouts_total 1443
telemt_upstream_connect_attempt_total 3218
telemt_upstream_connect_success_total 3180
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 3218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 8946
telemt_me_reconnect_success_total 2424
telemt_me_reader_eof_total 2688
telemt_me_idle_close_by_peer_total 2688
telemt_me_route_drop_no_conn_total 10829
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25235
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 97
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2645
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 2420
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 25229
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 221351568 (211.10 MB)
telemt_user_octets_to_client{user="hello"} 7306082976 (6.80 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 13963.7 (3h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114609
telemt_connections_bad_total 6940
telemt_handshake_timeouts_total 1276
telemt_upstream_connect_attempt_total 2893
telemt_upstream_connect_success_total 2837
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 2893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1416
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 7076
telemt_me_reconnect_success_total 2081
telemt_me_reader_eof_total 2284
telemt_me_idle_close_by_peer_total 2284
telemt_me_route_drop_no_conn_total 56639
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100539
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2256
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2077
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 100384
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 1683833412 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 51025870992 (47.52 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 88
```