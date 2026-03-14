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

# Server Metrics 2026-03-14 10:26:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 183174.2 (50h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 713808
telemt_connections_bad_total 33655
telemt_handshake_timeouts_total 13850
telemt_upstream_connect_attempt_total 46676
telemt_upstream_connect_success_total 46441
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 46676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 6020
telemt_me_reconnect_attempts_total 42692
telemt_me_reconnect_success_total 36931
telemt_me_reader_eof_total 39480
telemt_me_idle_close_by_peer_total 39479
telemt_me_route_drop_no_conn_total 236038
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 611229
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2418
telemt_desync_full_logged_total 810
telemt_desync_suppressed_total 1608
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 891
telemt_desync_frames_bucket_total{bucket="gt_10"} 1011
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 37506
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 36911
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 575
telemt_user_connections_total{user="hello"} 611109
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 17381231762 (16.19 GB)
telemt_user_octets_to_client{user="hello"} 290530029544 (270.58 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 183068.3 (50h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356874
telemt_connections_bad_total 2823
telemt_handshake_timeouts_total 3141
telemt_upstream_connect_attempt_total 154060
telemt_upstream_connect_success_total 152707
telemt_upstream_connect_fail_total 1353
telemt_upstream_connect_attempts_per_request{bucket="1"} 154060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38607
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2460
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1353
telemt_me_keepalive_timeout_total 5465
telemt_me_reconnect_attempts_total 188563
telemt_me_reconnect_success_total 40276
telemt_me_reader_eof_total 45975
telemt_me_idle_close_by_peer_total 45975
telemt_me_route_drop_no_conn_total 122825
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233757
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 45
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
telemt_me_writer_removed_unexpected_total 45293
telemt_me_refill_failed_total 4627
telemt_me_writer_restored_same_endpoint_total 40259
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5017
telemt_user_connections_total{user="hello"} 336861
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 3448852979 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 107528339067 (100.14 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 183031.6 (50h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 413845
telemt_connections_bad_total 3264
telemt_handshake_timeouts_total 35774
telemt_upstream_connect_attempt_total 48639
telemt_upstream_connect_success_total 48630
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 48639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26305
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3891
telemt_me_reconnect_attempts_total 40760
telemt_me_reconnect_success_total 39455
telemt_me_reader_eof_total 42410
telemt_me_idle_close_by_peer_total 42410
telemt_me_route_drop_no_conn_total 150403
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360173
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
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 39928
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 39434
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 359904
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 13957174732 (13.00 GB)
telemt_user_octets_to_client{user="hello"} 158511101076 (147.62 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 183007.5 (50h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 522598
telemt_connections_bad_total 16710
telemt_handshake_timeouts_total 5225
telemt_upstream_connect_attempt_total 78958
telemt_upstream_connect_success_total 68286
telemt_upstream_connect_fail_total 10672
telemt_upstream_connect_attempts_per_request{bucket="1"} 78958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10672
telemt_me_keepalive_timeout_total 5636
telemt_me_reconnect_attempts_total 152423
telemt_me_reconnect_success_total 40124
telemt_me_reader_eof_total 44925
telemt_me_idle_close_by_peer_total 44917
telemt_me_route_drop_no_conn_total 189410
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 447264
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2011
telemt_desync_full_logged_total 595
telemt_desync_suppressed_total 1416
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 771
telemt_desync_frames_bucket_total{bucket="gt_10"} 762
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 44088
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 40114
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3964
telemt_user_connections_total{user="hello"} 466131
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 9990002219 (9.30 GB)
telemt_user_octets_to_client{user="hello"} 193028437660 (179.77 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 133178.8 (36h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221789
telemt_connections_bad_total 34310
telemt_handshake_timeouts_total 1984
telemt_upstream_connect_attempt_total 46806
telemt_upstream_connect_success_total 46346
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 46806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_keepalive_timeout_total 2794
telemt_me_reconnect_attempts_total 50724
telemt_me_reconnect_success_total 34845
telemt_me_reader_eof_total 37278
telemt_me_idle_close_by_peer_total 37278
telemt_me_route_drop_no_conn_total 67092
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174664
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 35661
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34827
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 816
telemt_user_connections_total{user="hello"} 179421
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 2674502169 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 83947874667 (78.18 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 182963.7 (50h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1059953
telemt_connections_bad_total 36977
telemt_handshake_timeouts_total 26923
telemt_upstream_connect_attempt_total 38271
telemt_upstream_connect_success_total 38068
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 38270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 4870
telemt_me_reconnect_attempts_total 33695
telemt_me_reconnect_success_total 29006
telemt_me_reader_eof_total 31108
telemt_me_idle_close_by_peer_total 31105
telemt_me_route_drop_no_conn_total 496153
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 982563
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 29517
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28999
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 511
telemt_user_connections_total{user="hello"} 955174
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 17937180116 (16.71 GB)
telemt_user_octets_to_client{user="hello"} 480386011852 (447.39 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 54
```