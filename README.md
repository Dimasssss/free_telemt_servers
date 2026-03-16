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

# Server Metrics 2026-03-16 04:50:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 110155.9 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471107
telemt_connections_bad_total 5425
telemt_handshake_timeouts_total 15945
telemt_upstream_connect_attempt_total 26286
telemt_upstream_connect_success_total 26166
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 26286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14530
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 24129
telemt_me_reconnect_success_total 20702
telemt_me_reader_eof_total 22147
telemt_me_idle_close_by_peer_total 22147
telemt_me_route_drop_no_conn_total 505476
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 491842
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2418
telemt_desync_full_logged_total 960
telemt_desync_suppressed_total 1458
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 949
telemt_desync_frames_bucket_total{bucket="gt_10"} 980
telemt_pool_swap_total 106
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21032
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 20668
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 430702
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 8667014696 (8.07 GB)
telemt_user_octets_to_client{user="hello"} 299108246800 (278.57 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 110162.3 (30h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190440
telemt_connections_bad_total 2992
telemt_handshake_timeouts_total 14741
telemt_upstream_connect_attempt_total 29900
telemt_upstream_connect_success_total 29825
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 29900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 30858
telemt_me_reconnect_success_total 23949
telemt_me_reader_eof_total 25671
telemt_me_idle_close_by_peer_total 25670
telemt_me_route_drop_no_conn_total 96297
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165770
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 24499
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 23933
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 165313
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 3554653497 (3.31 GB)
telemt_user_octets_to_client{user="hello"} 87145521560 (81.16 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 110154.7 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212190
telemt_connections_bad_total 3734
telemt_handshake_timeouts_total 4154
telemt_upstream_connect_attempt_total 31022
telemt_upstream_connect_success_total 31014
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 31022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 32879
telemt_me_reconnect_success_total 25487
telemt_me_reader_eof_total 27458
telemt_me_idle_close_by_peer_total 27457
telemt_me_route_drop_no_conn_total 75141
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167295
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 25969
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 25479
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 167028
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 16489233421 (15.36 GB)
telemt_user_octets_to_client{user="hello"} 103757026076 (96.63 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 110154.4 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277750
telemt_connections_bad_total 1245
telemt_handshake_timeouts_total 2187
telemt_upstream_connect_attempt_total 25770
telemt_upstream_connect_success_total 25744
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 25770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 20401
telemt_me_reconnect_success_total 20278
telemt_me_reader_eof_total 21657
telemt_me_idle_close_by_peer_total 21656
telemt_me_route_drop_no_conn_total 102008
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256384
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 886
telemt_desync_full_logged_total 316
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 386
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 20529
telemt_me_writer_restored_same_endpoint_total 20267
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 256272
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 4323016984 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 114767735260 (106.89 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 85225.8 (23h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185792
telemt_connections_bad_total 32197
telemt_handshake_timeouts_total 3264
telemt_upstream_connect_attempt_total 24535
telemt_upstream_connect_success_total 24401
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 24535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 114482
telemt_me_reconnect_success_total 20007
telemt_me_reader_eof_total 21241
telemt_me_idle_close_by_peer_total 21241
telemt_me_route_drop_no_conn_total 59127
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145663
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 342
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 20167
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 19903
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 145298
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 2008868821 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 62124991175 (57.86 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 110153.7 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 704866
telemt_connections_bad_total 59343
telemt_handshake_timeouts_total 5296
telemt_upstream_connect_attempt_total 23417
telemt_upstream_connect_success_total 23291
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 23417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 19134
telemt_me_reconnect_success_total 17799
telemt_me_reader_eof_total 19006
telemt_me_idle_close_by_peer_total 19006
telemt_me_route_drop_no_conn_total 604628
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 723209
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18046
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 17772
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 581881
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 13319997176 (12.41 GB)
telemt_user_octets_to_client{user="hello"} 359616930508 (334.92 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 47
```