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

# Server Metrics 2026-03-15 15:34:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 62380.1 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284231
telemt_connections_bad_total 2776
telemt_handshake_timeouts_total 8780
telemt_upstream_connect_attempt_total 15644
telemt_upstream_connect_success_total 15561
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15812
telemt_me_reconnect_success_total 12430
telemt_me_reader_eof_total 13241
telemt_me_idle_close_by_peer_total 13241
telemt_me_route_drop_no_conn_total 447084
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322464
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1748
telemt_desync_full_logged_total 698
telemt_desync_suppressed_total 1050
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 745
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12665
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 12396
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 261566
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 5679122500 (5.29 GB)
telemt_user_octets_to_client{user="hello"} 220148838016 (205.03 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 62386.8 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107762
telemt_connections_bad_total 2807
telemt_handshake_timeouts_total 10250
telemt_upstream_connect_attempt_total 17217
telemt_upstream_connect_success_total 17217
telemt_upstream_connect_attempts_per_request{bucket="1"} 17217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16401
telemt_me_reconnect_success_total 14043
telemt_me_reader_eof_total 15014
telemt_me_idle_close_by_peer_total 15014
telemt_me_route_drop_no_conn_total 44695
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91450
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 14281
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 14027
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 91436
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 1834037408 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 46284285148 (43.11 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 62379.2 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115692
telemt_connections_bad_total 1660
telemt_handshake_timeouts_total 2888
telemt_upstream_connect_attempt_total 18418
telemt_upstream_connect_success_total 18410
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 18418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 22571
telemt_me_reconnect_success_total 15223
telemt_me_reader_eof_total 16357
telemt_me_idle_close_by_peer_total 16357
telemt_me_route_drop_no_conn_total 44562
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100318
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 15591
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 15215
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 100218
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 10350097196 (9.64 GB)
telemt_user_octets_to_client{user="hello"} 58181888384 (54.19 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 62379.1 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153409
telemt_connections_bad_total 872
telemt_handshake_timeouts_total 959
telemt_upstream_connect_attempt_total 15053
telemt_upstream_connect_success_total 15047
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 15053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11985
telemt_me_reconnect_success_total 11912
telemt_me_reader_eof_total 12673
telemt_me_idle_close_by_peer_total 12673
telemt_me_route_drop_no_conn_total 59781
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140729
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 496
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 333
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 12050
telemt_me_writer_restored_same_endpoint_total 11901
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 140642
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 2715952736 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 66921958776 (62.33 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 37450.6 (10h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90866
telemt_connections_bad_total 22142
telemt_handshake_timeouts_total 1809
telemt_upstream_connect_attempt_total 11605
telemt_upstream_connect_success_total 11536
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 11605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103910
telemt_me_reconnect_success_total 9476
telemt_me_reader_eof_total 9921
telemt_me_idle_close_by_peer_total 9921
telemt_me_route_drop_no_conn_total 31066
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64843
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 158
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 9508
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 9372
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 64979
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 909348921 (867.22 MB)
telemt_user_octets_to_client{user="hello"} 27501027215 (25.61 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 62378.7 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387013
telemt_connections_bad_total 49933
telemt_handshake_timeouts_total 3319
telemt_upstream_connect_attempt_total 13411
telemt_upstream_connect_success_total 13332
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 13411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 11466
telemt_me_reconnect_success_total 10170
telemt_me_reader_eof_total 10827
telemt_me_idle_close_by_peer_total 10827
telemt_me_route_drop_no_conn_total 214983
telemt_me_route_drop_channel_closed_total 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339053
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10312
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 10143
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 319879
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 8169474996 (7.61 GB)
telemt_user_octets_to_client{user="hello"} 168408483540 (156.84 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 83
```