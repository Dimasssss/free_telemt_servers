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

# Server Metrics 2026-03-14 01:41:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 151712.1 (42h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 597871
telemt_connections_bad_total 21993
telemt_handshake_timeouts_total 12883
telemt_upstream_connect_attempt_total 38749
telemt_upstream_connect_success_total 38558
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 38749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20788
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5501
telemt_me_reconnect_attempts_total 35272
telemt_me_reconnect_success_total 30597
telemt_me_reader_eof_total 32688
telemt_me_idle_close_by_peer_total 32687
telemt_me_route_drop_no_conn_total 196125
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511978
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1651
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 1084
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 675
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 31081
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 30581
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 484
telemt_user_connections_total{user="hello"} 511870
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 15574546766 (14.50 GB)
telemt_user_octets_to_client{user="hello"} 252197673492 (234.88 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 151604.6 (42h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306414
telemt_connections_bad_total 2237
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 143236
telemt_upstream_connect_success_total 142121
telemt_upstream_connect_fail_total 1115
telemt_upstream_connect_attempts_per_request{bucket="1"} 143236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1115
telemt_me_keepalive_timeout_total 3803
telemt_me_reconnect_attempts_total 162184
telemt_me_reconnect_success_total 31237
telemt_me_reader_eof_total 36135
telemt_me_idle_close_by_peer_total 36135
telemt_me_route_drop_no_conn_total 96815
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187384
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
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 35623
telemt_me_refill_failed_total 4086
telemt_me_writer_restored_same_endpoint_total 31220
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4386
telemt_user_connections_total{user="hello"} 290496
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 3037048915 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 90806645563 (84.57 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 151568.3 (42h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358740
telemt_connections_bad_total 2823
telemt_handshake_timeouts_total 33218
telemt_upstream_connect_attempt_total 40236
telemt_upstream_connect_success_total 40230
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 40236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3285
telemt_me_reconnect_attempts_total 33886
telemt_me_reconnect_success_total 32620
telemt_me_reader_eof_total 35054
telemt_me_idle_close_by_peer_total 35054
telemt_me_route_drop_no_conn_total 127547
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310197
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
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 33006
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 32600
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 310082
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 12613604264 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 127014232516 (118.29 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 151543.9 (42h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460121
telemt_connections_bad_total 15375
telemt_handshake_timeouts_total 4353
telemt_upstream_connect_attempt_total 68893
telemt_upstream_connect_success_total 58437
telemt_upstream_connect_fail_total 10456
telemt_upstream_connect_attempts_per_request{bucket="1"} 68893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 321
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10456
telemt_me_keepalive_timeout_total 5087
telemt_me_reconnect_attempts_total 137874
telemt_me_reconnect_success_total 31839
telemt_me_reader_eof_total 36065
telemt_me_idle_close_by_peer_total 36057
telemt_me_route_drop_no_conn_total 162622
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 389977
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 32
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
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 35535
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 31829
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3696
telemt_user_connections_total{user="hello"} 408819
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 9070658131 (8.45 GB)
telemt_user_octets_to_client{user="hello"} 157196987240 (146.40 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 101715.6 (28h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170014
telemt_connections_bad_total 24753
telemt_handshake_timeouts_total 1557
telemt_upstream_connect_attempt_total 37236
telemt_upstream_connect_success_total 36895
telemt_upstream_connect_fail_total 341
telemt_upstream_connect_attempts_per_request{bucket="1"} 37236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 341
telemt_me_keepalive_timeout_total 1388
telemt_me_reconnect_attempts_total 40362
telemt_me_reconnect_success_total 26948
telemt_me_reader_eof_total 28819
telemt_me_idle_close_by_peer_total 28819
telemt_me_route_drop_no_conn_total 50505
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133913
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
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 27612
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 26930
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 664
telemt_user_connections_total{user="hello"} 138718
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 1894803249 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 64339761715 (59.92 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 151500.0 (42h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 881962
telemt_connections_bad_total 27533
telemt_handshake_timeouts_total 25325
telemt_upstream_connect_attempt_total 31383
telemt_upstream_connect_success_total 31216
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 31383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 3492
telemt_me_reconnect_attempts_total 28364
telemt_me_reconnect_success_total 23697
telemt_me_reader_eof_total 25394
telemt_me_idle_close_by_peer_total 25391
telemt_me_route_drop_no_conn_total 420015
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 824266
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 24151
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23690
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 797022
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 14146100592 (13.17 GB)
telemt_user_octets_to_client{user="hello"} 406017638440 (378.13 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 27
```