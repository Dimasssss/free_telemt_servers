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

# Server Metrics 2026-03-15 20:55:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 81673.9 (22h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381091
telemt_connections_bad_total 4980
telemt_handshake_timeouts_total 13740
telemt_upstream_connect_attempt_total 19509
telemt_upstream_connect_success_total 19412
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 19509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10788
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 18756
telemt_me_reconnect_success_total 15353
telemt_me_reader_eof_total 16367
telemt_me_idle_close_by_peer_total 16367
telemt_me_route_drop_no_conn_total 480413
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408954
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2015
telemt_desync_full_logged_total 791
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 851
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 15629
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 15319
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 348016
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 7790953932 (7.26 GB)
telemt_user_octets_to_client{user="hello"} 264204713592 (246.06 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 81680.4 (22h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157776
telemt_connections_bad_total 2864
telemt_handshake_timeouts_total 13835
telemt_upstream_connect_attempt_total 22441
telemt_upstream_connect_success_total 22367
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 22441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 604
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 23437
telemt_me_reconnect_success_total 17896
telemt_me_reader_eof_total 19102
telemt_me_idle_close_by_peer_total 19101
telemt_me_route_drop_no_conn_total 65203
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134497
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 18340
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 17880
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 444
telemt_user_connections_total{user="hello"} 134767
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 2475214897 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 68326291288 (63.63 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 81673.0 (22h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156691
telemt_connections_bad_total 1734
telemt_handshake_timeouts_total 3395
telemt_upstream_connect_attempt_total 23405
telemt_upstream_connect_success_total 23397
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 23405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 26648
telemt_me_reconnect_success_total 19282
telemt_me_reader_eof_total 20712
telemt_me_idle_close_by_peer_total 20711
telemt_me_route_drop_no_conn_total 62291
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139174
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 19701
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 19274
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 139056
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 10931348016 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 81878041148 (76.25 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 81672.7 (22h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227225
telemt_connections_bad_total 1183
telemt_handshake_timeouts_total 1578
telemt_upstream_connect_attempt_total 19066
telemt_upstream_connect_success_total 19050
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 19066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 15084
telemt_me_reconnect_success_total 14992
telemt_me_reader_eof_total 15973
telemt_me_idle_close_by_peer_total 15973
telemt_me_route_drop_no_conn_total 83086
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209086
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 781
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 506
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 15173
telemt_me_writer_restored_same_endpoint_total 14981
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 209004
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 3877576612 (3.61 GB)
telemt_user_octets_to_client{user="hello"} 95219943456 (88.68 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 56744.3 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138335
telemt_connections_bad_total 26659
telemt_handshake_timeouts_total 2535
telemt_upstream_connect_attempt_total 16481
telemt_upstream_connect_success_total 16381
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 16481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 107833
telemt_me_reconnect_success_total 13379
telemt_me_reader_eof_total 14083
telemt_me_idle_close_by_peer_total 14083
telemt_me_route_drop_no_conn_total 46180
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105297
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 13469
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 13275
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 105425
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 1664566637 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 40461793639 (37.68 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 81672.1 (22h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 552309
telemt_connections_bad_total 58479
telemt_handshake_timeouts_total 4341
telemt_upstream_connect_attempt_total 17317
telemt_upstream_connect_success_total 17220
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8931
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 14444
telemt_me_reconnect_success_total 13133
telemt_me_reader_eof_total 13960
telemt_me_idle_close_by_peer_total 13960
telemt_me_route_drop_no_conn_total 409100
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 546885
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 323
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 13315
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 13106
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 468776
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 11780742720 (10.97 GB)
telemt_user_octets_to_client{user="hello"} 272195669768 (253.50 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 42
```