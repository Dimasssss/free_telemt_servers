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

# Server Metrics 2026-03-16 09:15:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 126089.8 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 601722
telemt_connections_bad_total 9415
telemt_handshake_timeouts_total 20907
telemt_upstream_connect_attempt_total 29571
telemt_upstream_connect_success_total 29430
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 29571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 26622
telemt_me_reconnect_success_total 23181
telemt_me_reader_eof_total 24762
telemt_me_idle_close_by_peer_total 24762
telemt_me_route_drop_no_conn_total 535811
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 591873
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2772
telemt_desync_full_logged_total 1086
telemt_desync_suppressed_total 1686
telemt_desync_frames_bucket_total{bucket="1_2"} 613
telemt_desync_frames_bucket_total{bucket="3_10"} 1062
telemt_desync_frames_bucket_total{bucket="gt_10"} 1097
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23543
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 23147
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 530644
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 10264073516 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 333668779228 (310.75 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 126096.5 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246525
telemt_connections_bad_total 3290
telemt_handshake_timeouts_total 15364
telemt_upstream_connect_attempt_total 33756
telemt_upstream_connect_success_total 33681
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 33756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 36297
telemt_me_reconnect_success_total 27007
telemt_me_reader_eof_total 28963
telemt_me_idle_close_by_peer_total 28962
telemt_me_route_drop_no_conn_total 118297
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219325
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 189
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 27674
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 26991
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 667
telemt_user_connections_total{user="hello"} 218877
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 4869184877 (4.53 GB)
telemt_user_octets_to_client{user="hello"} 120666785256 (112.38 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 126088.6 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257353
telemt_connections_bad_total 5755
telemt_handshake_timeouts_total 5385
telemt_upstream_connect_attempt_total 35097
telemt_upstream_connect_success_total 35089
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 35097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 36173
telemt_me_reconnect_success_total 28759
telemt_me_reader_eof_total 30927
telemt_me_idle_close_by_peer_total 30926
telemt_me_route_drop_no_conn_total 89312
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207906
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 100
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 29276
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 28751
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 207607
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 17645580241 (16.43 GB)
telemt_user_octets_to_client{user="hello"} 116539952516 (108.54 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 126088.2 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366170
telemt_connections_bad_total 1379
telemt_handshake_timeouts_total 3156
telemt_upstream_connect_attempt_total 29102
telemt_upstream_connect_success_total 29066
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 29102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14964
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22944
telemt_me_reconnect_success_total 22795
telemt_me_reader_eof_total 24335
telemt_me_idle_close_by_peer_total 24334
telemt_me_route_drop_no_conn_total 127564
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338396
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1248
telemt_desync_full_logged_total 428
telemt_desync_suppressed_total 820
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 535
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 23101
telemt_me_writer_restored_same_endpoint_total 22784
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 338271
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 5805702762 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 139300953748 (129.73 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 101159.6 (28h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233055
telemt_connections_bad_total 37012
telemt_handshake_timeouts_total 4235
telemt_upstream_connect_attempt_total 28892
telemt_upstream_connect_success_total 28734
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 28892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 118032
telemt_me_reconnect_success_total 23532
telemt_me_reader_eof_total 24988
telemt_me_idle_close_by_peer_total 24988
telemt_me_route_drop_no_conn_total 72854
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185149
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 597
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 459
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 23733
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 23428
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 184765
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 2441559405 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 78150817095 (72.78 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 126087.5 (35h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 848940
telemt_connections_bad_total 72548
telemt_handshake_timeouts_total 9877
telemt_upstream_connect_attempt_total 26360
telemt_upstream_connect_success_total 26222
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 26360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 21310
telemt_me_reconnect_success_total 19958
telemt_me_reader_eof_total 21306
telemt_me_idle_close_by_peer_total 21306
telemt_me_route_drop_no_conn_total 659290
telemt_me_route_drop_channel_closed_total 116
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 840156
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
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20239
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19931
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 698780
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 15033398968 (14.00 GB)
telemt_user_octets_to_client{user="hello"} 422848456920 (393.81 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 83
```