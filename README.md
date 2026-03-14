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

# Server Metrics 2026-03-14 02:42:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 155376.8 (43h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 604594
telemt_connections_bad_total 22812
telemt_handshake_timeouts_total 12917
telemt_upstream_connect_attempt_total 39694
telemt_upstream_connect_success_total 39497
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 39694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5515
telemt_me_reconnect_attempts_total 36039
telemt_me_reconnect_success_total 31360
telemt_me_reader_eof_total 33500
telemt_me_idle_close_by_peer_total 33499
telemt_me_route_drop_no_conn_total 198266
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517649
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1681
telemt_desync_full_logged_total 580
telemt_desync_suppressed_total 1101
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 636
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 31849
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 31340
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 489
telemt_user_connections_total{user="hello"} 517540
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 15640419114 (14.57 GB)
telemt_user_octets_to_client{user="hello"} 254732163596 (237.24 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 155269.6 (43h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309513
telemt_connections_bad_total 2261
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 144659
telemt_upstream_connect_success_total 143511
telemt_upstream_connect_fail_total 1148
telemt_upstream_connect_attempts_per_request{bucket="1"} 144659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1148
telemt_me_keepalive_timeout_total 3825
telemt_me_reconnect_attempts_total 164425
telemt_me_reconnect_success_total 32450
telemt_me_reader_eof_total 37413
telemt_me_idle_close_by_peer_total 37413
telemt_me_route_drop_no_conn_total 97915
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190341
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
telemt_me_writer_removed_unexpected_total 36880
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 32433
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4430
telemt_user_connections_total{user="hello"} 293453
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 3062660923 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 92347646979 (86.01 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 155233.3 (43h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362430
telemt_connections_bad_total 2830
telemt_handshake_timeouts_total 33755
telemt_upstream_connect_attempt_total 41215
telemt_upstream_connect_success_total 41209
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 41215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3297
telemt_me_reconnect_attempts_total 34693
telemt_me_reconnect_success_total 33423
telemt_me_reader_eof_total 35920
telemt_me_idle_close_by_peer_total 35920
telemt_me_route_drop_no_conn_total 129480
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313259
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
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 33815
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 33402
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 392
telemt_user_connections_total{user="hello"} 313089
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 12630544580 (11.76 GB)
telemt_user_octets_to_client{user="hello"} 127229206088 (118.49 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 155208.9 (43h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463461
telemt_connections_bad_total 15378
telemt_handshake_timeouts_total 4385
telemt_upstream_connect_attempt_total 70463
telemt_upstream_connect_success_total 59986
telemt_upstream_connect_fail_total 10477
telemt_upstream_connect_attempts_per_request{bucket="1"} 70463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 325
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10477
telemt_me_keepalive_timeout_total 5110
telemt_me_reconnect_attempts_total 139251
telemt_me_reconnect_success_total 33208
telemt_me_reader_eof_total 37508
telemt_me_idle_close_by_peer_total 37500
telemt_me_route_drop_no_conn_total 164119
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393005
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
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 36913
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 33198
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3705
telemt_user_connections_total{user="hello"} 411838
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 9088877367 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 159265400264 (148.33 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 105380.5 (29h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175746
telemt_connections_bad_total 25427
telemt_handshake_timeouts_total 1564
telemt_upstream_connect_attempt_total 38367
telemt_upstream_connect_success_total 38010
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 38367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_keepalive_timeout_total 2341
telemt_me_reconnect_attempts_total 41279
telemt_me_reconnect_success_total 27860
telemt_me_reader_eof_total 29809
telemt_me_idle_close_by_peer_total 29809
telemt_me_route_drop_no_conn_total 52063
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138939
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
telemt_me_writer_removed_unexpected_total 28532
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 27842
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 672
telemt_user_connections_total{user="hello"} 143718
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 2048261797 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 65018736015 (60.55 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 155164.9 (43h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 893350
telemt_connections_bad_total 27774
telemt_handshake_timeouts_total 25357
telemt_upstream_connect_attempt_total 32200
telemt_upstream_connect_success_total 32029
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 32200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 3499
telemt_me_reconnect_attempts_total 29005
telemt_me_reconnect_success_total 24338
telemt_me_reader_eof_total 26085
telemt_me_idle_close_by_peer_total 26082
telemt_me_route_drop_no_conn_total 425780
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 835192
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
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 24798
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24331
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 807949
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 14276307228 (13.30 GB)
telemt_user_octets_to_client{user="hello"} 410299939772 (382.12 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 40
```