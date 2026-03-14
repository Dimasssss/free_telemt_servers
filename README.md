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

# Server Metrics 2026-03-14 06:42:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 169739.0 (47h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 651958
telemt_connections_bad_total 32357
telemt_handshake_timeouts_total 13045
telemt_upstream_connect_attempt_total 43208
telemt_upstream_connect_success_total 42989
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 43208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5634
telemt_me_reconnect_attempts_total 38841
telemt_me_reconnect_success_total 34151
telemt_me_reader_eof_total 36520
telemt_me_idle_close_by_peer_total 36519
telemt_me_route_drop_no_conn_total 214600
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553860
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2035
telemt_desync_full_logged_total 695
telemt_desync_suppressed_total 1340
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 742
telemt_desync_frames_bucket_total{bucket="gt_10"} 851
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 34665
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34131
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 553744
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 16117509298 (15.01 GB)
telemt_user_octets_to_client{user="hello"} 267760327472 (249.37 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 169631.7 (47h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328727
telemt_connections_bad_total 2320
telemt_handshake_timeouts_total 2472
telemt_upstream_connect_attempt_total 149929
telemt_upstream_connect_success_total 148671
telemt_upstream_connect_fail_total 1258
telemt_upstream_connect_attempts_per_request{bucket="1"} 149929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1258
telemt_me_keepalive_timeout_total 3998
telemt_me_reconnect_attempts_total 177499
telemt_me_reconnect_success_total 36910
telemt_me_reader_eof_total 42279
telemt_me_idle_close_by_peer_total 42279
telemt_me_route_drop_no_conn_total 107561
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208170
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
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
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 41646
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 36893
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4736
telemt_user_connections_total{user="hello"} 311277
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 3244776935 (3.02 GB)
telemt_user_octets_to_client{user="hello"} 101459907091 (94.49 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 169595.1 (47h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383758
telemt_connections_bad_total 2970
telemt_handshake_timeouts_total 35069
telemt_upstream_connect_attempt_total 44825
telemt_upstream_connect_success_total 44816
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3471
telemt_me_reconnect_attempts_total 37606
telemt_me_reconnect_success_total 36320
telemt_me_reader_eof_total 39059
telemt_me_idle_close_by_peer_total 39059
telemt_me_route_drop_no_conn_total 138462
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332409
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
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 36758
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36299
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 438
telemt_user_connections_total{user="hello"} 332182
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 13445353224 (12.52 GB)
telemt_user_octets_to_client{user="hello"} 131239190032 (122.23 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 169570.6 (47h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484766
telemt_connections_bad_total 15855
telemt_handshake_timeouts_total 4497
telemt_upstream_connect_attempt_total 75133
telemt_upstream_connect_success_total 64563
telemt_upstream_connect_fail_total 10570
telemt_upstream_connect_attempts_per_request{bucket="1"} 75133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10570
telemt_me_keepalive_timeout_total 5393
telemt_me_reconnect_attempts_total 143137
telemt_me_reconnect_success_total 37077
telemt_me_reader_eof_total 41589
telemt_me_idle_close_by_peer_total 41581
telemt_me_route_drop_no_conn_total 174794
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 412483
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1762
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 669
telemt_desync_frames_bucket_total{bucket="gt_10"} 674
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 40815
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 37067
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3738
telemt_user_connections_total{user="hello"} 431326
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 9317887731 (8.68 GB)
telemt_user_octets_to_client{user="hello"} 177024517792 (164.87 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 119742.4 (33h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195400
telemt_connections_bad_total 28998
telemt_handshake_timeouts_total 1701
telemt_upstream_connect_attempt_total 42403
telemt_upstream_connect_success_total 42002
telemt_upstream_connect_fail_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 42403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 401
telemt_me_keepalive_timeout_total 2464
telemt_me_reconnect_attempts_total 44595
telemt_me_reconnect_success_total 31167
telemt_me_reader_eof_total 33362
telemt_me_idle_close_by_peer_total 33362
telemt_me_route_drop_no_conn_total 58024
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154493
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 633
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 483
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 31873
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31149
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 706
telemt_user_connections_total{user="hello"} 159242
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 2366459001 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 72649757327 (67.66 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 169526.8 (47h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 968182
telemt_connections_bad_total 36042
telemt_handshake_timeouts_total 26050
telemt_upstream_connect_attempt_total 35204
telemt_upstream_connect_success_total 35016
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 35204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 4696
telemt_me_reconnect_attempts_total 31301
telemt_me_reconnect_success_total 26623
telemt_me_reader_eof_total 28582
telemt_me_idle_close_by_peer_total 28579
telemt_me_route_drop_no_conn_total 456714
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 897743
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 27107
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26616
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 484
telemt_user_connections_total{user="hello"} 870391
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 14995082444 (13.97 GB)
telemt_user_octets_to_client{user="hello"} 439661588160 (409.47 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 71
```