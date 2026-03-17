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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 00:43:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 21484.2 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125298
telemt_connections_bad_total 1924
telemt_handshake_timeouts_total 4964
telemt_upstream_connect_attempt_total 4449
telemt_upstream_connect_success_total 4424
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 4449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3362
telemt_me_reconnect_success_total 3350
telemt_me_reader_eof_total 3547
telemt_me_idle_close_by_peer_total 3547
telemt_me_route_drop_no_conn_total 38292
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113109
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 615
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 301
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3372
telemt_me_writer_restored_same_endpoint_total 3329
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 113061
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 1655970580 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 54031770900 (50.32 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 21735.5 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74327
telemt_connections_bad_total 871
telemt_handshake_timeouts_total 2832
telemt_upstream_connect_attempt_total 5066
telemt_upstream_connect_success_total 4998
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 5066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_reconnect_attempts_total 3898
telemt_me_reconnect_success_total 3889
telemt_me_reader_eof_total 4114
telemt_me_idle_close_by_peer_total 4114
telemt_me_route_drop_no_conn_total 30222
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67551
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3936
telemt_me_writer_restored_same_endpoint_total 3873
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 67494
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 1061936772 (1012.74 MB)
telemt_user_octets_to_client{user="hello"} 32963362720 (30.70 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 21511.7 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42415
telemt_connections_bad_total 460
telemt_handshake_timeouts_total 1757
telemt_upstream_connect_attempt_total 5630
telemt_upstream_connect_success_total 5597
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 5630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 4540
telemt_me_reconnect_success_total 4513
telemt_me_reader_eof_total 4814
telemt_me_idle_close_by_peer_total 4814
telemt_me_route_drop_no_conn_total 14133
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39068
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4565
telemt_me_writer_restored_same_endpoint_total 4502
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 39063
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 649169800 (619.10 MB)
telemt_user_octets_to_client{user="hello"} 14158243992 (13.19 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 21570.9 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74256
telemt_connections_bad_total 3046
telemt_handshake_timeouts_total 470
telemt_upstream_connect_attempt_total 4923
telemt_upstream_connect_success_total 4874
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 4923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 3820
telemt_me_reconnect_success_total 3793
telemt_me_reader_eof_total 4005
telemt_me_idle_close_by_peer_total 4005
telemt_me_route_drop_no_conn_total 25119
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68708
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 144
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3838
telemt_me_writer_restored_same_endpoint_total 3786
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 68692
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 855736256 (816.09 MB)
telemt_user_octets_to_client{user="hello"} 30227349580 (28.15 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 21542.9 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54608
telemt_connections_bad_total 14437
telemt_handshake_timeouts_total 279
telemt_upstream_connect_attempt_total 6003
telemt_upstream_connect_success_total 5919
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 6003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_reconnect_attempts_total 5960
telemt_me_reconnect_success_total 4841
telemt_me_reader_eof_total 5064
telemt_me_idle_close_by_peer_total 5064
telemt_me_route_drop_no_conn_total 15135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38237
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4970
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 4833
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 38233
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 298762000 (284.92 MB)
telemt_user_octets_to_client{user="hello"} 13442123360 (12.52 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 21703.9 (6h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133057
telemt_connections_bad_total 4356
telemt_handshake_timeouts_total 962
telemt_upstream_connect_attempt_total 4413
telemt_upstream_connect_success_total 4388
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 4413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2298
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 3284
telemt_me_reconnect_success_total 3276
telemt_me_reader_eof_total 3491
telemt_me_idle_close_by_peer_total 3491
telemt_me_route_drop_no_conn_total 153488
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193414
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 115
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3320
telemt_me_writer_restored_same_endpoint_total 3266
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 123206
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 2122655328 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 106255863696 (98.96 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 9710.3 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 4560
telemt_upstream_connect_success_total 4560
telemt_upstream_connect_attempts_per_request{bucket="1"} 4560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4061
telemt_me_reconnect_success_total 4040
telemt_me_reader_eof_total 4428
telemt_me_idle_close_by_peer_total 4428
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4077
telemt_me_writer_restored_same_endpoint_total 4040
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```