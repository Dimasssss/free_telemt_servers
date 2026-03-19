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

# Server Metrics 2026-03-19 06:34:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 31532.6 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 503808
telemt_connections_bad_total 54650
telemt_connections_current 1224
telemt_connections_me_current 1224
telemt_handshake_timeouts_total 22410
telemt_upstream_connect_attempt_total 6051
telemt_upstream_connect_success_total 5947
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 6051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5526
telemt_me_reconnect_success_total 4383
telemt_me_reader_eof_total 4653
telemt_me_idle_close_by_peer_total 4652
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 135777
telemt_me_route_drop_channel_closed_total 38
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375099
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2380
telemt_desync_full_logged_total 690
telemt_desync_suppressed_total 1690
telemt_desync_frames_bucket_total{bucket="1_2"} 801
telemt_desync_frames_bucket_total{bucket="3_10"} 932
telemt_desync_frames_bucket_total{bucket="gt_10"} 647
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4464
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4366
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 372344
telemt_user_connections_current{user="hello"} 1224
telemt_user_octets_from_client{user="hello"} 5017751056 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 126320433904 (117.65 GB)
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 31536.7 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1065862
telemt_connections_bad_total 61048
telemt_connections_current 3697
telemt_connections_me_current 3697
telemt_handshake_timeouts_total 28858
telemt_upstream_connect_attempt_total 5887
telemt_upstream_connect_success_total 5780
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 5887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 5350
telemt_me_reconnect_success_total 4204
telemt_me_reader_eof_total 4463
telemt_me_idle_close_by_peer_total 4463
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 346409
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 882228
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3750
telemt_desync_full_logged_total 1291
telemt_desync_suppressed_total 2459
telemt_desync_frames_bucket_total{bucket="1_2"} 676
telemt_desync_frames_bucket_total{bucket="3_10"} 1415
telemt_desync_frames_bucket_total{bucket="gt_10"} 1659
telemt_pool_swap_total 27
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4316
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4184
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 882182
telemt_user_connections_current{user="hello"} 3697
telemt_user_octets_from_client{user="hello"} 19120128216 (17.81 GB)
telemt_user_octets_to_client{user="hello"} 392215354616 (365.28 GB)
telemt_user_unique_ips_current{user="hello"} 1301
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 31587.1 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 979268
telemt_connections_bad_total 88445
telemt_connections_current 2698
telemt_connections_me_current 2698
telemt_handshake_timeouts_total 23484
telemt_upstream_connect_attempt_total 5565
telemt_upstream_connect_success_total 5565
telemt_upstream_connect_attempts_per_request{bucket="1"} 5565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5008
telemt_me_reconnect_success_total 3957
telemt_me_reader_eof_total 4205
telemt_me_idle_close_by_peer_total 4204
telemt_me_route_drop_no_conn_total 311118
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 663885
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2560
telemt_desync_full_logged_total 917
telemt_desync_suppressed_total 1643
telemt_desync_frames_bucket_total{bucket="1_2"} 448
telemt_desync_frames_bucket_total{bucket="3_10"} 1017
telemt_desync_frames_bucket_total{bucket="gt_10"} 1095
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4047
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 3933
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 662781
telemt_user_connections_current{user="hello"} 2698
telemt_user_octets_from_client{user="hello"} 10259069732 (9.55 GB)
telemt_user_octets_to_client{user="hello"} 252324916484 (235.00 GB)
telemt_user_unique_ips_current{user="hello"} 947
telemt_user_unique_ips_recent_window{user="hello"} 417
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 31530.3 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1207402
telemt_connections_bad_total 345025
telemt_connections_current 3006
telemt_connections_me_current 3006
telemt_handshake_timeouts_total 29431
telemt_upstream_connect_attempt_total 5591
telemt_upstream_connect_success_total 5556
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 5591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 4010
telemt_me_reconnect_success_total 3981
telemt_me_reader_eof_total 4215
telemt_me_idle_close_by_peer_total 4215
telemt_me_route_drop_no_conn_total 294068
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 712294
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3539
telemt_desync_full_logged_total 1136
telemt_desync_suppressed_total 2403
telemt_desync_frames_bucket_total{bucket="1_2"} 797
telemt_desync_frames_bucket_total{bucket="3_10"} 1569
telemt_desync_frames_bucket_total{bucket="gt_10"} 1173
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4028
telemt_me_writer_restored_same_endpoint_total 3957
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 712110
telemt_user_connections_current{user="hello"} 3006
telemt_user_octets_from_client{user="hello"} 17177773116 (16.00 GB)
telemt_user_octets_to_client{user="hello"} 375721218516 (349.92 GB)
telemt_user_unique_ips_current{user="hello"} 1074
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 31542.0 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200032
telemt_connections_bad_total 12213
telemt_connections_current 691
telemt_connections_me_current 691
telemt_handshake_timeouts_total 1584
telemt_upstream_connect_attempt_total 8401
telemt_upstream_connect_success_total 8190
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 8401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_reconnect_attempts_total 11063
telemt_me_reconnect_success_total 6625
telemt_me_reader_eof_total 7017
telemt_me_idle_close_by_peer_total 7017
telemt_me_route_drop_no_conn_total 81078
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175228
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 264
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 6791
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6595
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 175219
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 2818632504 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 94228135204 (87.76 GB)
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 31532.7 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 736434
telemt_connections_bad_total 85344
telemt_connections_current 2747
telemt_connections_me_current 2747
telemt_handshake_timeouts_total 32102
telemt_upstream_connect_attempt_total 6274
telemt_upstream_connect_success_total 6274
telemt_upstream_connect_attempts_per_request{bucket="1"} 6274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4722
telemt_me_reconnect_success_total 4708
telemt_me_reader_eof_total 4978
telemt_me_idle_close_by_peer_total 4978
telemt_me_route_drop_no_conn_total 256392
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 591934
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3376
telemt_desync_full_logged_total 1198
telemt_desync_suppressed_total 2178
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 1301
telemt_desync_frames_bucket_total{bucket="gt_10"} 1416
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4761
telemt_me_writer_restored_same_endpoint_total 4693
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 591739
telemt_user_connections_current{user="hello"} 2747
telemt_user_octets_from_client{user="hello"} 8710519280 (8.11 GB)
telemt_user_octets_to_client{user="hello"} 334701609704 (311.72 GB)
telemt_user_unique_ips_current{user="hello"} 900
telemt_user_unique_ips_recent_window{user="hello"} 395
```