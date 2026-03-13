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

# Server Metrics 2026-03-13 10:55:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 98502.5 (27h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393728
telemt_connections_bad_total 3194
telemt_handshake_timeouts_total 8133
telemt_upstream_connect_attempt_total 24928
telemt_upstream_connect_success_total 24812
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 24928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1791
telemt_me_reconnect_attempts_total 23383
telemt_me_reconnect_success_total 19861
telemt_me_reader_eof_total 21218
telemt_me_idle_close_by_peer_total 21217
telemt_me_route_drop_no_conn_total 123093
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339760
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1080
telemt_desync_full_logged_total 401
telemt_desync_suppressed_total 679
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 20178
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19845
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 317
telemt_user_connections_total{user="hello"} 339443
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 6041995372 (5.63 GB)
telemt_user_octets_to_client{user="hello"} 147432773408 (137.31 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 98396.2 (27h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180355
telemt_connections_bad_total 1595
telemt_handshake_timeouts_total 1381
telemt_upstream_connect_attempt_total 47794
telemt_upstream_connect_success_total 47126
telemt_upstream_connect_fail_total 668
telemt_upstream_connect_attempts_per_request{bucket="1"} 47794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19576
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 668
telemt_me_keepalive_timeout_total 782
telemt_me_reconnect_attempts_total 88550
telemt_me_reconnect_success_total 25701
telemt_me_reader_eof_total 28421
telemt_me_idle_close_by_peer_total 28421
telemt_me_route_drop_no_conn_total 76953
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153599
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 27886
telemt_me_refill_failed_total 1960
telemt_me_writer_restored_same_endpoint_total 25684
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2185
telemt_user_connections_total{user="hello"} 169878
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 1747387780 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 56977824759 (53.06 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 98360.0 (27h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219906
telemt_connections_bad_total 2050
telemt_handshake_timeouts_total 4672
telemt_upstream_connect_attempt_total 26614
telemt_upstream_connect_success_total 26611
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 26614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 782
telemt_me_reconnect_attempts_total 22831
telemt_me_reconnect_success_total 21631
telemt_me_reader_eof_total 23184
telemt_me_idle_close_by_peer_total 23184
telemt_me_route_drop_no_conn_total 82231
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205100
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 64
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 21866
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 21611
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 205021
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 9229997852 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 86458265876 (80.52 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 98335.5 (27h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308814
telemt_connections_bad_total 13676
telemt_handshake_timeouts_total 2270
telemt_upstream_connect_attempt_total 39145
telemt_upstream_connect_success_total 29107
telemt_upstream_connect_fail_total 10038
telemt_upstream_connect_attempts_per_request{bucket="1"} 39145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10038
telemt_me_keepalive_timeout_total 3446
telemt_me_reconnect_attempts_total 85991
telemt_me_reconnect_success_total 21322
telemt_me_reader_eof_total 23989
telemt_me_idle_close_by_peer_total 23982
telemt_me_route_drop_no_conn_total 111827
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265364
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 968
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23611
telemt_me_refill_failed_total 2016
telemt_me_writer_restored_same_endpoint_total 21312
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2289
telemt_user_connections_total{user="hello"} 268085
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 5707731970 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 99840744297 (92.98 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 48507.0 (13h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66787
telemt_connections_bad_total 9684
telemt_handshake_timeouts_total 726
telemt_upstream_connect_attempt_total 16991
telemt_upstream_connect_success_total 16828
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 16991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 438
telemt_me_reconnect_attempts_total 18912
telemt_me_reconnect_success_total 14410
telemt_me_reader_eof_total 15354
telemt_me_idle_close_by_peer_total 15354
telemt_me_route_drop_no_conn_total 21043
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54331
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 81
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 14681
telemt_me_refill_failed_total 139
telemt_me_writer_restored_same_endpoint_total 14392
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 54327
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 490083544 (467.38 MB)
telemt_user_octets_to_client{user="hello"} 14653725892 (13.65 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 98292.1 (27h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 544995
telemt_connections_bad_total 14515
telemt_handshake_timeouts_total 9765
telemt_upstream_connect_attempt_total 20973
telemt_upstream_connect_success_total 20864
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 20973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1622
telemt_me_reconnect_attempts_total 20570
telemt_me_reconnect_success_total 15952
telemt_me_reader_eof_total 17131
telemt_me_idle_close_by_peer_total 17128
telemt_me_route_drop_no_conn_total 276182
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 528562
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 438
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 272
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 16307
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 15945
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 355
telemt_user_connections_total{user="hello"} 501640
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 9187652788 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 277076924996 (258.05 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 67
```