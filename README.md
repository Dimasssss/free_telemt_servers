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

# Server Metrics 2026-03-12 12:38:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 18286.9 (5h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97579
telemt_connections_bad_total 539
telemt_handshake_timeouts_total 3465
telemt_upstream_connect_attempt_total 4487
telemt_upstream_connect_success_total 4466
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 207
telemt_me_reconnect_attempts_total 3522
telemt_me_reconnect_success_total 3500
telemt_me_reader_eof_total 3660
telemt_me_idle_close_by_peer_total 3659
telemt_me_route_drop_no_conn_total 27204
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87538
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 413
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 254
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3522
telemt_me_writer_restored_same_endpoint_total 3484
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 87505
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 1211648088 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 28759598192 (26.78 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 18179.8 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39420
telemt_connections_bad_total 334
telemt_handshake_timeouts_total 307
telemt_upstream_connect_attempt_total 5520
telemt_upstream_connect_success_total 5379
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 5520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 19454
telemt_me_reconnect_success_total 4431
telemt_me_reader_eof_total 4943
telemt_me_idle_close_by_peer_total 4943
telemt_me_route_drop_no_conn_total 16951
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37492
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
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
telemt_me_writer_removed_unexpected_total 4916
telemt_me_refill_failed_total 469
telemt_me_writer_restored_same_endpoint_total 4416
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 37493
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 428553736 (408.70 MB)
telemt_user_octets_to_client{user="hello"} 9754189056 (9.08 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 18143.6 (5h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53211
telemt_connections_bad_total 130
telemt_handshake_timeouts_total 517
telemt_upstream_connect_attempt_total 5010
telemt_upstream_connect_success_total 5010
telemt_upstream_connect_attempts_per_request{bucket="1"} 5010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 4066
telemt_me_reconnect_success_total 4036
telemt_me_reader_eof_total 4249
telemt_me_idle_close_by_peer_total 4249
telemt_me_route_drop_no_conn_total 18564
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50098
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4057
telemt_me_writer_restored_same_endpoint_total 4016
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 50081
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 1617909600 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 31931759164 (29.74 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 18119.2 (5h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67661
telemt_connections_bad_total 1082
telemt_handshake_timeouts_total 320
telemt_upstream_connect_attempt_total 4843
telemt_upstream_connect_success_total 4720
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 4842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 183
telemt_me_reconnect_attempts_total 10312
telemt_me_reconnect_success_total 3768
telemt_me_reader_eof_total 4096
telemt_me_idle_close_by_peer_total 4096
telemt_me_route_drop_no_conn_total 22766
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61960
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 180
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4020
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 3760
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 61962
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 1097814188 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 30277777112 (28.20 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18088.6 (5h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37715
telemt_connections_bad_total 3432
telemt_handshake_timeouts_total 640
telemt_upstream_connect_attempt_total 6891
telemt_upstream_connect_success_total 6665
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 6891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 21763
telemt_me_reconnect_success_total 3581
telemt_me_reader_eof_total 4146
telemt_me_idle_close_by_peer_total 4146
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 11156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30511
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 380
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 311
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4170
telemt_me_refill_failed_total 569
telemt_me_writer_restored_same_endpoint_total 3564
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 589
telemt_user_connections_total{user="hello"} 32658
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 229949170 (219.30 MB)
telemt_user_octets_to_client{user="hello"} 8252860966 (7.69 GB)
telemt_user_msgs_from_client{user="hello"} 24844
telemt_user_msgs_to_client{user="hello"} 108729
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 18075.5 (5h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101810
telemt_connections_bad_total 760
telemt_handshake_timeouts_total 922
telemt_upstream_connect_attempt_total 3590
telemt_upstream_connect_success_total 3573
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 3590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 2668
telemt_me_reconnect_success_total 2646
telemt_me_reader_eof_total 2787
telemt_me_idle_close_by_peer_total 2787
telemt_me_route_drop_no_conn_total 41967
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96845
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 205
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 137
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2679
telemt_me_writer_restored_same_endpoint_total 2639
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 96812
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 2449950916 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 46748406800 (43.54 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 44
```