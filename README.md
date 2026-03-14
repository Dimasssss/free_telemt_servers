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

# Server Metrics 2026-03-14 09:30:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 179817.4 (49h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 696058
telemt_connections_bad_total 32629
telemt_handshake_timeouts_total 13588
telemt_upstream_connect_attempt_total 45655
telemt_upstream_connect_success_total 45424
telemt_upstream_connect_fail_total 231
telemt_upstream_connect_attempts_per_request{bucket="1"} 45655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 231
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5867
telemt_me_reconnect_attempts_total 40798
telemt_me_reconnect_success_total 36097
telemt_me_reader_eof_total 38582
telemt_me_idle_close_by_peer_total 38581
telemt_me_route_drop_no_conn_total 229978
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595316
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2362
telemt_desync_full_logged_total 787
telemt_desync_suppressed_total 1575
telemt_desync_frames_bucket_total{bucket="1_2"} 502
telemt_desync_frames_bucket_total{bucket="3_10"} 869
telemt_desync_frames_bucket_total{bucket="gt_10"} 991
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 36628
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 36077
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 531
telemt_user_connections_total{user="hello"} 595194
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 17228459906 (16.05 GB)
telemt_user_octets_to_client{user="hello"} 285936696580 (266.30 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 179710.5 (49h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350270
telemt_connections_bad_total 2787
telemt_handshake_timeouts_total 3063
telemt_upstream_connect_attempt_total 153246
telemt_upstream_connect_success_total 151904
telemt_upstream_connect_fail_total 1342
telemt_upstream_connect_attempts_per_request{bucket="1"} 153246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38267
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1342
telemt_me_keepalive_timeout_total 5377
telemt_me_reconnect_attempts_total 185217
telemt_me_reconnect_success_total 39652
telemt_me_reader_eof_total 45252
telemt_me_idle_close_by_peer_total 45252
telemt_me_route_drop_no_conn_total 118852
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227451
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 44
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 44579
telemt_me_refill_failed_total 4542
telemt_me_writer_restored_same_endpoint_total 39635
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4927
telemt_user_connections_total{user="hello"} 330555
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 3414620123 (3.18 GB)
telemt_user_octets_to_client{user="hello"} 105987599679 (98.71 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 179674.2 (49h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406833
telemt_connections_bad_total 3206
telemt_handshake_timeouts_total 35644
telemt_upstream_connect_attempt_total 47662
telemt_upstream_connect_success_total 47653
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 47662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3677
telemt_me_reconnect_attempts_total 39959
telemt_me_reconnect_success_total 38660
telemt_me_reader_eof_total 41552
telemt_me_idle_close_by_peer_total 41552
telemt_me_route_drop_no_conn_total 147506
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353659
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 39124
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38639
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 353385
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 13748956048 (12.80 GB)
telemt_user_octets_to_client{user="hello"} 156126246448 (145.40 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 179649.8 (49h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 512745
telemt_connections_bad_total 16613
telemt_handshake_timeouts_total 4673
telemt_upstream_connect_attempt_total 77954
telemt_upstream_connect_success_total 67299
telemt_upstream_connect_fail_total 10655
telemt_upstream_connect_attempts_per_request{bucket="1"} 77954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10655
telemt_me_keepalive_timeout_total 5551
telemt_me_reconnect_attempts_total 150446
telemt_me_reconnect_success_total 39321
telemt_me_reader_eof_total 44045
telemt_me_idle_close_by_peer_total 44037
telemt_me_route_drop_no_conn_total 185761
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 438446
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1955
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 1377
telemt_desync_frames_bucket_total{bucket="1_2"} 458
telemt_desync_frames_bucket_total{bucket="3_10"} 755
telemt_desync_frames_bucket_total{bucket="gt_10"} 742
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 43241
telemt_me_refill_failed_total 3465
telemt_me_writer_restored_same_endpoint_total 39311
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3920
telemt_user_connections_total{user="hello"} 457327
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 9835380423 (9.16 GB)
telemt_user_octets_to_client{user="hello"} 190419127248 (177.34 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 129821.1 (36h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214787
telemt_connections_bad_total 33210
telemt_handshake_timeouts_total 1925
telemt_upstream_connect_attempt_total 45868
telemt_upstream_connect_success_total 45422
telemt_upstream_connect_fail_total 446
telemt_upstream_connect_attempts_per_request{bucket="1"} 45868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 446
telemt_me_keepalive_timeout_total 2654
telemt_me_reconnect_attempts_total 49929
telemt_me_reconnect_success_total 34055
telemt_me_reader_eof_total 36439
telemt_me_idle_close_by_peer_total 36439
telemt_me_route_drop_no_conn_total 64621
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168957
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 740
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 560
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 34860
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34037
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 805
telemt_user_connections_total{user="hello"} 173718
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 2632201813 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 82124974711 (76.48 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 179606.1 (49h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1036765
telemt_connections_bad_total 36864
telemt_handshake_timeouts_total 26735
telemt_upstream_connect_attempt_total 37451
telemt_upstream_connect_success_total 37252
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 37451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 4832
telemt_me_reconnect_attempts_total 33057
telemt_me_reconnect_success_total 28372
telemt_me_reader_eof_total 30435
telemt_me_idle_close_by_peer_total 30432
telemt_me_route_drop_no_conn_total 486275
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 960618
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 798
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 536
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 28874
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28365
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 502
telemt_user_connections_total{user="hello"} 933235
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 17146414944 (15.97 GB)
telemt_user_octets_to_client{user="hello"} 465432355640 (433.47 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 67
```