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

# Server Metrics 2026-03-14 09:55:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 181344.4 (50h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 703405
telemt_connections_bad_total 32893
telemt_handshake_timeouts_total 13685
telemt_upstream_connect_attempt_total 46057
telemt_upstream_connect_success_total 45823
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 46057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5902
telemt_me_reconnect_attempts_total 41110
telemt_me_reconnect_success_total 36408
telemt_me_reader_eof_total 38918
telemt_me_idle_close_by_peer_total 38917
telemt_me_route_drop_no_conn_total 232421
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 602054
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2385
telemt_desync_full_logged_total 796
telemt_desync_suppressed_total 1589
telemt_desync_frames_bucket_total{bucket="1_2"} 508
telemt_desync_frames_bucket_total{bucket="3_10"} 877
telemt_desync_frames_bucket_total{bucket="gt_10"} 1000
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 36945
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 36388
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 601932
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 17294081170 (16.11 GB)
telemt_user_octets_to_client{user="hello"} 287271011444 (267.54 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 181238.1 (50h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353437
telemt_connections_bad_total 2814
telemt_handshake_timeouts_total 3100
telemt_upstream_connect_attempt_total 153601
telemt_upstream_connect_success_total 152255
telemt_upstream_connect_fail_total 1346
telemt_upstream_connect_attempts_per_request{bucket="1"} 153601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2446
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1346
telemt_me_keepalive_timeout_total 5406
telemt_me_reconnect_attempts_total 188199
telemt_me_reconnect_success_total 39912
telemt_me_reader_eof_total 45598
telemt_me_idle_close_by_peer_total 45598
telemt_me_route_drop_no_conn_total 120737
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230460
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 44925
telemt_me_refill_failed_total 4627
telemt_me_writer_restored_same_endpoint_total 39895
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5013
telemt_user_connections_total{user="hello"} 333564
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 3431359407 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 106843386111 (99.51 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 181201.8 (50h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409995
telemt_connections_bad_total 3214
telemt_handshake_timeouts_total 35666
telemt_upstream_connect_attempt_total 48030
telemt_upstream_connect_success_total 48021
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 48030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3715
telemt_me_reconnect_attempts_total 40241
telemt_me_reconnect_success_total 38938
telemt_me_reader_eof_total 41860
telemt_me_idle_close_by_peer_total 41860
telemt_me_route_drop_no_conn_total 148864
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356651
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
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 39408
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38917
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 356378
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 13809113072 (12.86 GB)
telemt_user_octets_to_client{user="hello"} 157294523060 (146.49 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 181177.3 (50h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517691
telemt_connections_bad_total 16708
telemt_handshake_timeouts_total 5206
telemt_upstream_connect_attempt_total 78487
telemt_upstream_connect_success_total 67825
telemt_upstream_connect_fail_total 10662
telemt_upstream_connect_attempts_per_request{bucket="1"} 78487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27811
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 349
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10662
telemt_me_keepalive_timeout_total 5558
telemt_me_reconnect_attempts_total 152050
telemt_me_reconnect_success_total 39755
telemt_me_reader_eof_total 44542
telemt_me_idle_close_by_peer_total 44534
telemt_me_route_drop_no_conn_total 187492
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442624
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1974
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1390
telemt_desync_frames_bucket_total{bucket="1_2"} 464
telemt_desync_frames_bucket_total{bucket="3_10"} 763
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 43716
telemt_me_refill_failed_total 3501
telemt_me_writer_restored_same_endpoint_total 39745
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3961
telemt_user_connections_total{user="hello"} 461494
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 9908806795 (9.23 GB)
telemt_user_octets_to_client{user="hello"} 191338900148 (178.20 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 131348.9 (36h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217731
telemt_connections_bad_total 33498
telemt_handshake_timeouts_total 1963
telemt_upstream_connect_attempt_total 46319
telemt_upstream_connect_success_total 45868
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 46319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_timeout_total 2680
telemt_me_reconnect_attempts_total 50332
telemt_me_reconnect_success_total 34456
telemt_me_reader_eof_total 36868
telemt_me_idle_close_by_peer_total 36868
telemt_me_route_drop_no_conn_total 65651
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171513
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 758
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 572
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 360
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 35263
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 34438
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 807
telemt_user_connections_total{user="hello"} 176272
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 2644834789 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 82796776419 (77.11 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 181133.6 (50h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1047550
telemt_connections_bad_total 36935
telemt_handshake_timeouts_total 26804
telemt_upstream_connect_attempt_total 37826
telemt_upstream_connect_success_total 37625
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 37826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 4849
telemt_me_reconnect_attempts_total 33339
telemt_me_reconnect_success_total 28654
telemt_me_reader_eof_total 30732
telemt_me_idle_close_by_peer_total 30729
telemt_me_route_drop_no_conn_total 490519
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 970778
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 805
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 277
telemt_pool_swap_total 170
telemt_me_writer_removed_unexpected_total 29160
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28647
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 943397
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 17769237372 (16.55 GB)
telemt_user_octets_to_client{user="hello"} 472246140972 (439.81 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 63
```