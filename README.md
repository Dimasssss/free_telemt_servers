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

# Server Metrics 2026-03-12 11:16:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13376.7 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70328
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 2650
telemt_upstream_connect_attempt_total 3250
telemt_upstream_connect_success_total 3237
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 2561
telemt_me_reconnect_success_total 2545
telemt_me_reader_eof_total 2646
telemt_me_idle_close_by_peer_total 2645
telemt_me_route_drop_no_conn_total 19357
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63636
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 265
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2559
telemt_me_writer_restored_same_endpoint_total 2529
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 63640
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 932095320 (888.92 MB)
telemt_user_octets_to_client{user="hello"} 21508175072 (20.03 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 13270.5 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28405
telemt_connections_bad_total 265
telemt_handshake_timeouts_total 258
telemt_upstream_connect_attempt_total 4618
telemt_upstream_connect_success_total 4520
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 4618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 11465
telemt_me_reconnect_success_total 3835
telemt_me_reader_eof_total 4116
telemt_me_idle_close_by_peer_total 4116
telemt_me_route_drop_no_conn_total 11601
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26941
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 4087
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 3820
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 26939
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 280456844 (267.46 MB)
telemt_user_octets_to_client{user="hello"} 6142365388 (5.72 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 13234.1 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39692
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 337
telemt_upstream_connect_attempt_total 3638
telemt_upstream_connect_success_total 3638
telemt_upstream_connect_attempts_per_request{bucket="1"} 3638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 2959
telemt_me_reconnect_success_total 2941
telemt_me_reader_eof_total 3083
telemt_me_idle_close_by_peer_total 3083
telemt_me_route_drop_no_conn_total 13203
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37207
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2947
telemt_me_writer_restored_same_endpoint_total 2921
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 37194
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 494843720 (471.92 MB)
telemt_user_octets_to_client{user="hello"} 30139888892 (28.07 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 13209.9 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48499
telemt_connections_bad_total 1037
telemt_handshake_timeouts_total 256
telemt_upstream_connect_attempt_total 3930
telemt_upstream_connect_success_total 3842
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 3930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 166
telemt_me_reconnect_attempts_total 4339
telemt_me_reconnect_success_total 3146
telemt_me_reader_eof_total 3296
telemt_me_idle_close_by_peer_total 3296
telemt_me_route_drop_no_conn_total 15286
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43999
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 168
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3227
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 3138
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 43998
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 952273968 (908.16 MB)
telemt_user_octets_to_client{user="hello"} 26391601228 (24.58 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13179.2 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25332
telemt_connections_bad_total 2517
telemt_handshake_timeouts_total 394
telemt_upstream_connect_attempt_total 4104
telemt_upstream_connect_success_total 3943
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 4104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 14615
telemt_me_reconnect_success_total 3253
telemt_me_reader_eof_total 3604
telemt_me_idle_close_by_peer_total 3604
telemt_me_seq_mismatch_total 6
telemt_me_route_drop_no_conn_total 7506
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21705
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 335
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 235
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3627
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 3237
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 374
telemt_user_connections_total{user="hello"} 21702
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 135269824 (129.00 MB)
telemt_user_octets_to_client{user="hello"} 5666449096 (5.28 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 13166.2 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68776
telemt_connections_bad_total 585
telemt_handshake_timeouts_total 724
telemt_upstream_connect_attempt_total 2595
telemt_upstream_connect_success_total 2581
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 1914
telemt_me_reconnect_success_total 1900
telemt_me_reader_eof_total 1995
telemt_me_idle_close_by_peer_total 1995
telemt_me_route_drop_no_conn_total 29786
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65065
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 164
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1921
telemt_me_writer_restored_same_endpoint_total 1893
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 65028
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 2014688268 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 35017643840 (32.61 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 51
```