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

# Server Metrics 2026-03-13 10:17:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 96239.4 (26h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381956
telemt_connections_bad_total 3192
telemt_handshake_timeouts_total 8085
telemt_upstream_connect_attempt_total 24300
telemt_upstream_connect_success_total 24188
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 24300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1754
telemt_me_reconnect_attempts_total 22889
telemt_me_reconnect_success_total 19370
telemt_me_reader_eof_total 20689
telemt_me_idle_close_by_peer_total 20688
telemt_me_route_drop_no_conn_total 119377
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328711
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1073
telemt_desync_full_logged_total 396
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 19681
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19354
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 328415
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 5776698080 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 142835851708 (133.03 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 96132.3 (26h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175058
telemt_connections_bad_total 1563
telemt_handshake_timeouts_total 1322
telemt_upstream_connect_attempt_total 47318
telemt_upstream_connect_success_total 46668
telemt_upstream_connect_fail_total 650
telemt_upstream_connect_attempts_per_request{bucket="1"} 47318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 650
telemt_me_keepalive_timeout_total 736
telemt_me_reconnect_attempts_total 84367
telemt_me_reconnect_success_total 25380
telemt_me_reader_eof_total 27972
telemt_me_idle_close_by_peer_total 27972
telemt_me_route_drop_no_conn_total 74846
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148523
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 20
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
telemt_me_writer_removed_unexpected_total 27438
telemt_me_refill_failed_total 1840
telemt_me_writer_restored_same_endpoint_total 25364
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2058
telemt_user_connections_total{user="hello"} 164803
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 1714591372 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 54423339723 (50.69 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 96095.8 (26h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213218
telemt_connections_bad_total 2046
telemt_handshake_timeouts_total 4282
telemt_upstream_connect_attempt_total 25998
telemt_upstream_connect_success_total 25995
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 740
telemt_me_reconnect_attempts_total 22348
telemt_me_reconnect_success_total 21151
telemt_me_reader_eof_total 22664
telemt_me_idle_close_by_peer_total 22664
telemt_me_route_drop_no_conn_total 80109
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199109
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 21383
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 21131
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 199030
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 9177242456 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 81678998072 (76.07 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 96071.6 (26h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301565
telemt_connections_bad_total 13675
telemt_handshake_timeouts_total 2230
telemt_upstream_connect_attempt_total 38813
telemt_upstream_connect_success_total 28792
telemt_upstream_connect_fail_total 10021
telemt_upstream_connect_attempts_per_request{bucket="1"} 38813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10021
telemt_me_keepalive_timeout_total 3433
telemt_me_reconnect_attempts_total 81710
telemt_me_reconnect_success_total 21138
telemt_me_reader_eof_total 23676
telemt_me_idle_close_by_peer_total 23669
telemt_me_route_drop_no_conn_total 108838
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258672
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 966
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23298
telemt_me_refill_failed_total 1888
telemt_me_writer_restored_same_endpoint_total 21128
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2160
telemt_user_connections_total{user="hello"} 261394
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 5656681890 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 97653577625 (90.95 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 46243.1 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62183
telemt_connections_bad_total 9252
telemt_handshake_timeouts_total 492
telemt_upstream_connect_attempt_total 16031
telemt_upstream_connect_success_total 15875
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 16031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 400
telemt_me_reconnect_attempts_total 15777
telemt_me_reconnect_success_total 13547
telemt_me_reader_eof_total 14412
telemt_me_idle_close_by_peer_total 14412
telemt_me_route_drop_no_conn_total 19301
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50588
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 13739
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 13529
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 50583
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 464041088 (442.54 MB)
telemt_user_octets_to_client{user="hello"} 13592392356 (12.66 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 96028.1 (26h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525581
telemt_connections_bad_total 14507
telemt_handshake_timeouts_total 7582
telemt_upstream_connect_attempt_total 20516
telemt_upstream_connect_success_total 20409
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 20516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1582
telemt_me_reconnect_attempts_total 19289
telemt_me_reconnect_success_total 15634
telemt_me_reader_eof_total 16761
telemt_me_idle_close_by_peer_total 16758
telemt_me_route_drop_no_conn_total 270188
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511912
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 423
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 262
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 15954
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 15627
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 484994
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 8658807620 (8.06 GB)
telemt_user_octets_to_client{user="hello"} 272862899848 (254.12 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 69
```