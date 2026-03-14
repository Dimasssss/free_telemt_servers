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

# Server Metrics 2026-03-14 11:57:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 188669.4 (52h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 743640
telemt_connections_bad_total 34703
telemt_handshake_timeouts_total 14403
telemt_upstream_connect_attempt_total 47947
telemt_upstream_connect_success_total 47709
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 47947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6327
telemt_me_reconnect_attempts_total 43697
telemt_me_reconnect_success_total 37930
telemt_me_reader_eof_total 40554
telemt_me_idle_close_by_peer_total 40553
telemt_me_route_drop_no_conn_total 245112
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 638239
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2688
telemt_desync_full_logged_total 898
telemt_desync_suppressed_total 1790
telemt_desync_frames_bucket_total{bucket="1_2"} 556
telemt_desync_frames_bucket_total{bucket="3_10"} 1009
telemt_desync_frames_bucket_total{bucket="gt_10"} 1123
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 38515
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37910
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 638140
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 17727377006 (16.51 GB)
telemt_user_octets_to_client{user="hello"} 306784794524 (285.72 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 188562.2 (52h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369208
telemt_connections_bad_total 2847
telemt_handshake_timeouts_total 3338
telemt_upstream_connect_attempt_total 156646
telemt_upstream_connect_success_total 155256
telemt_upstream_connect_fail_total 1390
telemt_upstream_connect_attempts_per_request{bucket="1"} 156646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2485
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1390
telemt_me_keepalive_timeout_total 5696
telemt_me_reconnect_attempts_total 196448
telemt_me_reconnect_success_total 41819
telemt_me_reader_eof_total 47732
telemt_me_idle_close_by_peer_total 47732
telemt_me_route_drop_no_conn_total 127483
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244747
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 47
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
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 47050
telemt_me_refill_failed_total 4824
telemt_me_writer_restored_same_endpoint_total 41801
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5231
telemt_user_connections_total{user="hello"} 348568
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 3539750408 (3.30 GB)
telemt_user_octets_to_client{user="hello"} 112359118769 (104.64 GB)
telemt_user_msgs_from_client{user="hello"} 1697098
telemt_user_msgs_to_client{user="hello"} 9461508
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 188525.8 (52h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426610
telemt_connections_bad_total 3315
telemt_handshake_timeouts_total 36555
telemt_upstream_connect_attempt_total 50324
telemt_upstream_connect_success_total 50315
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 50324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4287
telemt_me_reconnect_attempts_total 42134
telemt_me_reconnect_success_total 40811
telemt_me_reader_eof_total 43849
telemt_me_idle_close_by_peer_total 43849
telemt_me_route_drop_no_conn_total 155865
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 371461
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 41302
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40790
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 491
telemt_user_connections_total{user="hello"} 371221
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 15429582046 (14.37 GB)
telemt_user_octets_to_client{user="hello"} 162881040639 (151.69 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 188501.6 (52h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 541512
telemt_connections_bad_total 16775
telemt_handshake_timeouts_total 5298
telemt_upstream_connect_attempt_total 80694
telemt_upstream_connect_success_total 69988
telemt_upstream_connect_fail_total 10706
telemt_upstream_connect_attempts_per_request{bucket="1"} 80694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28903
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 388
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10706
telemt_me_keepalive_timeout_total 5838
telemt_me_reconnect_attempts_total 156194
telemt_me_reconnect_success_total 41552
telemt_me_reader_eof_total 46462
telemt_me_idle_close_by_peer_total 46454
telemt_me_route_drop_no_conn_total 196048
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 464362
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2125
telemt_desync_full_logged_total 625
telemt_desync_suppressed_total 1500
telemt_desync_frames_bucket_total{bucket="1_2"} 495
telemt_desync_frames_bucket_total{bucket="3_10"} 805
telemt_desync_frames_bucket_total{bucket="gt_10"} 825
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 45611
telemt_me_refill_failed_total 3574
telemt_me_writer_restored_same_endpoint_total 41542
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4059
telemt_user_connections_total{user="hello"} 483228
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 10202530191 (9.50 GB)
telemt_user_octets_to_client{user="hello"} 196574016368 (183.07 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 138673.0 (38h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234918
telemt_connections_bad_total 37619
telemt_handshake_timeouts_total 2148
telemt_upstream_connect_attempt_total 48742
telemt_upstream_connect_success_total 48249
telemt_upstream_connect_fail_total 493
telemt_upstream_connect_attempts_per_request{bucket="1"} 48742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 493
telemt_me_keepalive_timeout_total 3123
telemt_me_reconnect_attempts_total 52348
telemt_me_reconnect_success_total 36459
telemt_me_reader_eof_total 38971
telemt_me_idle_close_by_peer_total 38971
telemt_me_route_drop_no_conn_total 71098
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183986
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 799
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 605
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 375
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 37297
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 36441
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 838
telemt_user_connections_total{user="hello"} 188741
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 2753109409 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 86780311007 (80.82 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 188457.5 (52h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1098666
telemt_connections_bad_total 37679
telemt_handshake_timeouts_total 27183
telemt_upstream_connect_attempt_total 39323
telemt_upstream_connect_success_total 39117
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 39323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 5184
telemt_me_reconnect_attempts_total 34480
telemt_me_reconnect_success_total 29785
telemt_me_reader_eof_total 31939
telemt_me_idle_close_by_peer_total 31936
telemt_me_route_drop_no_conn_total 515926
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1018814
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 30309
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29778
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 524
telemt_user_connections_total{user="hello"} 991398
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 21223480912 (19.77 GB)
telemt_user_octets_to_client{user="hello"} 496209506892 (462.13 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 60
```