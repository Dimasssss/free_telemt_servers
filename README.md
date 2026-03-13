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

# Server Metrics 2026-03-13 12:27:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 104035.1 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424307
telemt_connections_bad_total 3210
telemt_handshake_timeouts_total 8364
telemt_upstream_connect_attempt_total 26453
telemt_upstream_connect_success_total 26328
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 26453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2395
telemt_me_reconnect_attempts_total 24635
telemt_me_reconnect_success_total 21110
telemt_me_reader_eof_total 22535
telemt_me_idle_close_by_peer_total 22534
telemt_me_route_drop_no_conn_total 134571
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368578
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1241
telemt_desync_full_logged_total 440
telemt_desync_suppressed_total 801
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 459
telemt_desync_frames_bucket_total{bucket="gt_10"} 532
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 21437
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21094
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 368171
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 6559469492 (6.11 GB)
telemt_user_octets_to_client{user="hello"} 157606116820 (146.78 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 103927.7 (28h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196121
telemt_connections_bad_total 1657
telemt_handshake_timeouts_total 1478
telemt_upstream_connect_attempt_total 57974
telemt_upstream_connect_success_total 57273
telemt_upstream_connect_fail_total 701
telemt_upstream_connect_attempts_per_request{bucket="1"} 57974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 572
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 701
telemt_me_keepalive_timeout_total 1353
telemt_me_reconnect_attempts_total 96969
telemt_me_reconnect_success_total 25951
telemt_me_reader_eof_total 28931
telemt_me_idle_close_by_peer_total 28931
telemt_me_route_drop_no_conn_total 79133
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159078
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 23
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
telemt_me_writer_removed_unexpected_total 28395
telemt_me_refill_failed_total 2215
telemt_me_writer_restored_same_endpoint_total 25934
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2444
telemt_user_connections_total{user="hello"} 184975
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 1879106079 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 61107536869 (56.91 GB)
telemt_user_msgs_from_client{user="hello"} 386355
telemt_user_msgs_to_client{user="hello"} 2856195
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 103891.5 (28h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238079
telemt_connections_bad_total 2065
telemt_handshake_timeouts_total 7601
telemt_upstream_connect_attempt_total 28204
telemt_upstream_connect_success_total 28200
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2175
telemt_me_reconnect_attempts_total 24157
telemt_me_reconnect_success_total 22946
telemt_me_reader_eof_total 24582
telemt_me_idle_close_by_peer_total 24582
telemt_me_route_drop_no_conn_total 88304
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219788
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 23198
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 22926
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 219702
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 9353075144 (8.71 GB)
telemt_user_octets_to_client{user="hello"} 98002200768 (91.27 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 103866.8 (28h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331988
telemt_connections_bad_total 14093
telemt_handshake_timeouts_total 2448
telemt_upstream_connect_attempt_total 40015
telemt_upstream_connect_success_total 29939
telemt_upstream_connect_fail_total 10076
telemt_upstream_connect_attempts_per_request{bucket="1"} 40015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10076
telemt_me_keepalive_timeout_total 4049
telemt_me_reconnect_attempts_total 93232
telemt_me_reconnect_success_total 21680
telemt_me_reader_eof_total 24568
telemt_me_idle_close_by_peer_total 24561
telemt_me_route_drop_no_conn_total 119952
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286397
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 999
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 703
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 367
telemt_desync_frames_bucket_total{bucket="gt_10"} 383
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 24186
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 21670
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2506
telemt_user_connections_total{user="hello"} 289308
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 5949516598 (5.54 GB)
telemt_user_octets_to_client{user="hello"} 109106205821 (101.61 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 54038.4 (15h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78638
telemt_connections_bad_total 10679
telemt_handshake_timeouts_total 925
telemt_upstream_connect_attempt_total 23359
telemt_upstream_connect_success_total 23178
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 23359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 943
telemt_me_reconnect_attempts_total 25480
telemt_me_reconnect_success_total 15563
telemt_me_reader_eof_total 16703
telemt_me_idle_close_by_peer_total 16703
telemt_me_route_drop_no_conn_total 23205
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59590
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 120
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 16009
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15545
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 446
telemt_user_connections_total{user="hello"} 64501
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 560888437 (534.90 MB)
telemt_user_octets_to_client{user="hello"} 18096474567 (16.85 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 103823.4 (28h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593740
telemt_connections_bad_total 17527
telemt_handshake_timeouts_total 14291
telemt_upstream_connect_attempt_total 22048
telemt_upstream_connect_success_total 21933
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 22048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2486
telemt_me_reconnect_attempts_total 21373
telemt_me_reconnect_success_total 16752
telemt_me_reader_eof_total 17981
telemt_me_idle_close_by_peer_total 17978
telemt_me_route_drop_no_conn_total 292306
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 568587
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 17114
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16745
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 541650
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 9612584600 (8.95 GB)
telemt_user_octets_to_client{user="hello"} 289215582512 (269.35 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 64
```