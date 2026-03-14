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

# Server Metrics 2026-03-14 03:08:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 156904.5 (43h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 609599
telemt_connections_bad_total 25303
telemt_handshake_timeouts_total 12927
telemt_upstream_connect_attempt_total 40135
telemt_upstream_connect_success_total 39933
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 40135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5540
telemt_me_reconnect_attempts_total 36389
telemt_me_reconnect_success_total 31708
telemt_me_reader_eof_total 33882
telemt_me_idle_close_by_peer_total 33881
telemt_me_route_drop_no_conn_total 199288
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520069
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1711
telemt_desync_full_logged_total 587
telemt_desync_suppressed_total 1124
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 143
telemt_me_writer_removed_unexpected_total 32201
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 31688
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 519960
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 15665077466 (14.59 GB)
telemt_user_octets_to_client{user="hello"} 255584230428 (238.03 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 156797.7 (43h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310883
telemt_connections_bad_total 2264
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 145218
telemt_upstream_connect_success_total 144064
telemt_upstream_connect_fail_total 1154
telemt_upstream_connect_attempts_per_request{bucket="1"} 145218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1154
telemt_me_keepalive_timeout_total 3833
telemt_me_reconnect_attempts_total 164892
telemt_me_reconnect_success_total 32916
telemt_me_reader_eof_total 37918
telemt_me_idle_close_by_peer_total 37918
telemt_me_route_drop_no_conn_total 98323
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191642
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 37349
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 32899
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4433
telemt_user_connections_total{user="hello"} 294754
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 3086546355 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 94326952935 (87.85 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 156761.3 (43h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364120
telemt_connections_bad_total 2910
telemt_handshake_timeouts_total 34181
telemt_upstream_connect_attempt_total 41597
telemt_upstream_connect_success_total 41591
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 41597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3314
telemt_me_reconnect_attempts_total 34989
telemt_me_reconnect_success_total 33717
telemt_me_reader_eof_total 36233
telemt_me_idle_close_by_peer_total 36233
telemt_me_route_drop_no_conn_total 129962
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 314406
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
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
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 34110
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 33696
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 393
telemt_user_connections_total{user="hello"} 314227
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 12637789180 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 127490016340 (118.73 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 156736.8 (43h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465267
telemt_connections_bad_total 15380
telemt_handshake_timeouts_total 4389
telemt_upstream_connect_attempt_total 70830
telemt_upstream_connect_success_total 60346
telemt_upstream_connect_fail_total 10484
telemt_upstream_connect_attempts_per_request{bucket="1"} 70830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23777
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10484
telemt_me_keepalive_timeout_total 5111
telemt_me_reconnect_attempts_total 139524
telemt_me_reconnect_success_total 33480
telemt_me_reader_eof_total 37790
telemt_me_idle_close_by_peer_total 37782
telemt_me_route_drop_no_conn_total 164959
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 394580
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 37185
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 33470
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3705
telemt_user_connections_total{user="hello"} 413410
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 9107393623 (8.48 GB)
telemt_user_octets_to_client{user="hello"} 160654666512 (149.62 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 106908.5 (29h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177675
telemt_connections_bad_total 25704
telemt_handshake_timeouts_total 1570
telemt_upstream_connect_attempt_total 38820
telemt_upstream_connect_success_total 38461
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 38820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_keepalive_timeout_total 2350
telemt_me_reconnect_attempts_total 41669
telemt_me_reconnect_success_total 28250
telemt_me_reader_eof_total 30231
telemt_me_idle_close_by_peer_total 30231
telemt_me_route_drop_no_conn_total 52650
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140573
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 28924
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 28232
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 674
telemt_user_connections_total{user="hello"} 145339
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 2113478777 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 65784273503 (61.27 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 156692.9 (43h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 898228
telemt_connections_bad_total 27827
telemt_handshake_timeouts_total 25378
telemt_upstream_connect_attempt_total 32564
telemt_upstream_connect_success_total 32393
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 32564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 3502
telemt_me_reconnect_attempts_total 29281
telemt_me_reconnect_success_total 24614
telemt_me_reader_eof_total 26375
telemt_me_idle_close_by_peer_total 26372
telemt_me_route_drop_no_conn_total 428528
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 840031
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 727
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 490
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 25075
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24607
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 812696
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 14305965340 (13.32 GB)
telemt_user_octets_to_client{user="hello"} 411443468384 (383.19 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 30
```