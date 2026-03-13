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

# Server Metrics 2026-03-13 20:10:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 131849.2 (36h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557300
telemt_connections_bad_total 14644
telemt_handshake_timeouts_total 12572
telemt_upstream_connect_attempt_total 33439
telemt_upstream_connect_success_total 33268
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 33439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5051
telemt_me_reconnect_attempts_total 30939
telemt_me_reconnect_success_total 26287
telemt_me_reader_eof_total 28056
telemt_me_idle_close_by_peer_total 28055
telemt_me_route_drop_no_conn_total 184192
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 480508
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1535
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 26727
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26271
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 480403
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 8873190938 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 232236710348 (216.29 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 131743.4 (36h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280949
telemt_connections_bad_total 2098
telemt_handshake_timeouts_total 1880
telemt_upstream_connect_attempt_total 131446
telemt_upstream_connect_success_total 130482
telemt_upstream_connect_fail_total 964
telemt_upstream_connect_attempts_per_request{bucket="1"} 131446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 964
telemt_me_keepalive_timeout_total 3628
telemt_me_reconnect_attempts_total 139364
telemt_me_reconnect_success_total 26390
telemt_me_reader_eof_total 30654
telemt_me_idle_close_by_peer_total 30654
telemt_me_route_drop_no_conn_total 83857
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169102
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 33
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
telemt_me_writer_removed_unexpected_total 30165
telemt_me_refill_failed_total 3525
telemt_me_writer_restored_same_endpoint_total 26373
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3775
telemt_user_connections_total{user="hello"} 266401
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 2743816973 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 79991732778 (74.50 GB)
telemt_user_msgs_from_client{user="hello"} 1564558
telemt_user_msgs_to_client{user="hello"} 8561591
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 131706.9 (36h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327165
telemt_connections_bad_total 2636
telemt_handshake_timeouts_total 23389
telemt_upstream_connect_attempt_total 34920
telemt_upstream_connect_success_total 34915
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2802
telemt_me_reconnect_attempts_total 29528
telemt_me_reconnect_success_total 28290
telemt_me_reader_eof_total 30357
telemt_me_idle_close_by_peer_total 30357
telemt_me_route_drop_no_conn_total 117162
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289726
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 28610
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28270
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 289637
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 11825353512 (11.01 GB)
telemt_user_octets_to_client{user="hello"} 120843924760 (112.54 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 131682.4 (36h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432382
telemt_connections_bad_total 15228
telemt_handshake_timeouts_total 4167
telemt_upstream_connect_attempt_total 63090
telemt_upstream_connect_success_total 52783
telemt_upstream_connect_fail_total 10307
telemt_upstream_connect_attempts_per_request{bucket="1"} 63090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10307
telemt_me_keepalive_timeout_total 4754
telemt_me_reconnect_attempts_total 120289
telemt_me_reconnect_success_total 27169
telemt_me_reader_eof_total 30850
telemt_me_idle_close_by_peer_total 30843
telemt_me_route_drop_no_conn_total 149978
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363476
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1481
telemt_desync_full_logged_total 441
telemt_desync_suppressed_total 1040
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 561
telemt_desync_frames_bucket_total{bucket="gt_10"} 565
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 30421
telemt_me_refill_failed_total 2904
telemt_me_writer_restored_same_endpoint_total 27159
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3252
telemt_user_connections_total{user="hello"} 382340
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 8663974891 (8.07 GB)
telemt_user_octets_to_client{user="hello"} 138836837940 (129.30 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 81853.9 (22h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139568
telemt_connections_bad_total 18063
telemt_handshake_timeouts_total 1436
telemt_upstream_connect_attempt_total 31223
telemt_upstream_connect_success_total 30925
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 31223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 1263
telemt_me_reconnect_attempts_total 35344
telemt_me_reconnect_success_total 21953
telemt_me_reader_eof_total 23505
telemt_me_idle_close_by_peer_total 23505
telemt_me_route_drop_no_conn_total 43429
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110702
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 604
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22574
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21935
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 115596
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 1359062017 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 51351699795 (47.82 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 131638.5 (36h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806298
telemt_connections_bad_total 24816
telemt_handshake_timeouts_total 24913
telemt_upstream_connect_attempt_total 27177
telemt_upstream_connect_success_total 27033
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 27177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 3089
telemt_me_reconnect_attempts_total 25136
telemt_me_reconnect_success_total 20489
telemt_me_reader_eof_total 21979
telemt_me_idle_close_by_peer_total 21976
telemt_me_route_drop_no_conn_total 383700
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 756226
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 20908
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20482
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 729085
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 12615388020 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 357568526116 (333.01 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 54
```