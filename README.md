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

# Server Metrics 2026-03-14 02:32:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 154765.4 (42h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 603647
telemt_connections_bad_total 22682
telemt_handshake_timeouts_total 12917
telemt_upstream_connect_attempt_total 39500
telemt_upstream_connect_success_total 39305
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 39500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5512
telemt_me_reconnect_attempts_total 35890
telemt_me_reconnect_success_total 31212
telemt_me_reader_eof_total 33342
telemt_me_idle_close_by_peer_total 33341
telemt_me_route_drop_no_conn_total 197912
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516864
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1676
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 1098
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 631
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 31701
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 31196
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 489
telemt_user_connections_total{user="hello"} 516755
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 15627257346 (14.55 GB)
telemt_user_octets_to_client{user="hello"} 254226398224 (236.77 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 154658.4 (42h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309073
telemt_connections_bad_total 2249
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 144346
telemt_upstream_connect_success_total 143207
telemt_upstream_connect_fail_total 1139
telemt_upstream_connect_attempts_per_request{bucket="1"} 144346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1139
telemt_me_keepalive_timeout_total 3815
telemt_me_reconnect_attempts_total 163140
telemt_me_reconnect_success_total 32189
telemt_me_reader_eof_total 37114
telemt_me_idle_close_by_peer_total 37114
telemt_me_route_drop_no_conn_total 97805
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189938
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 39
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
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 36581
telemt_me_refill_failed_total 4086
telemt_me_writer_restored_same_endpoint_total 32172
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4392
telemt_user_connections_total{user="hello"} 293050
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 3057059543 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 91914966891 (85.60 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 154621.9 (42h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361679
telemt_connections_bad_total 2829
telemt_handshake_timeouts_total 33527
telemt_upstream_connect_attempt_total 41030
telemt_upstream_connect_success_total 41024
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 41030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22226
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3297
telemt_me_reconnect_attempts_total 34551
telemt_me_reconnect_success_total 33282
telemt_me_reader_eof_total 35764
telemt_me_idle_close_by_peer_total 35764
telemt_me_route_drop_no_conn_total 129145
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312763
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
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 33673
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 33262
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 312593
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 12628774576 (11.76 GB)
telemt_user_octets_to_client{user="hello"} 127209952448 (118.47 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 154597.6 (42h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462825
telemt_connections_bad_total 15378
telemt_handshake_timeouts_total 4385
telemt_upstream_connect_attempt_total 70213
telemt_upstream_connect_success_total 59738
telemt_upstream_connect_fail_total 10475
telemt_upstream_connect_attempts_per_request{bucket="1"} 70213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23479
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10475
telemt_me_keepalive_timeout_total 5105
telemt_me_reconnect_attempts_total 139046
telemt_me_reconnect_success_total 33004
telemt_me_reader_eof_total 37265
telemt_me_idle_close_by_peer_total 37257
telemt_me_route_drop_no_conn_total 163818
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392457
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
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 36707
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 32994
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3703
telemt_user_connections_total{user="hello"} 411290
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 9085059651 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 158800802044 (147.89 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 104769.2 (29h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175114
telemt_connections_bad_total 25316
telemt_handshake_timeouts_total 1564
telemt_upstream_connect_attempt_total 38197
telemt_upstream_connect_success_total 37844
telemt_upstream_connect_fail_total 353
telemt_upstream_connect_attempts_per_request{bucket="1"} 38197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 353
telemt_me_keepalive_timeout_total 2338
telemt_me_reconnect_attempts_total 41138
telemt_me_reconnect_success_total 27720
telemt_me_reader_eof_total 29666
telemt_me_idle_close_by_peer_total 29666
telemt_me_route_drop_no_conn_total 51865
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138423
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 28389
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 27702
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 669
telemt_user_connections_total{user="hello"} 143202
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 2023685665 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 64988354943 (60.53 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 154553.7 (42h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 891420
telemt_connections_bad_total 27747
telemt_handshake_timeouts_total 25354
telemt_upstream_connect_attempt_total 32040
telemt_upstream_connect_success_total 31870
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 32040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 3497
telemt_me_reconnect_attempts_total 28889
telemt_me_reconnect_success_total 24222
telemt_me_reader_eof_total 25957
telemt_me_idle_close_by_peer_total 25954
telemt_me_route_drop_no_conn_total 424986
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 833314
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 708
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 24682
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24215
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 806071
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 14262921372 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 409391000636 (381.28 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 40
```