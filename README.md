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

# Server Metrics 2026-03-18 06:22:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 128223.5 (35h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1578468
telemt_connections_bad_total 10696
telemt_handshake_timeouts_total 36267
telemt_upstream_connect_attempt_total 27849
telemt_upstream_connect_success_total 27330
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 27849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 35811
telemt_me_reconnect_success_total 18656
telemt_me_reader_eof_total 20224
telemt_me_idle_close_by_peer_total 20223
telemt_me_route_drop_no_conn_total 628054
telemt_me_route_drop_channel_closed_total 173
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1368688
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8332
telemt_desync_full_logged_total 2512
telemt_desync_suppressed_total 5820
telemt_desync_frames_bucket_total{bucket="1_2"} 2180
telemt_desync_frames_bucket_total{bucket="3_10"} 3201
telemt_desync_frames_bucket_total{bucket="gt_10"} 2951
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19471
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18634
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 815
telemt_user_connections_total{user="hello"} 1362920
telemt_user_connections_current{user="hello"} 1032
telemt_user_octets_from_client{user="hello"} 32299348051 (30.08 GB)
telemt_user_octets_to_client{user="hello"} 489016270783 (455.43 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 392
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 128475.4 (35h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1691021
telemt_connections_bad_total 82037
telemt_handshake_timeouts_total 54525
telemt_upstream_connect_attempt_total 471267
telemt_upstream_connect_success_total 469630
telemt_upstream_connect_fail_total 1637
telemt_upstream_connect_attempts_per_request{bucket="1"} 471267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1637
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 127060
telemt_me_reconnect_success_total 20327
telemt_me_reader_eof_total 22638
telemt_me_idle_close_by_peer_total 22625
telemt_me_route_drop_no_conn_total 450112
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1032008
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4725
telemt_desync_full_logged_total 1647
telemt_desync_suppressed_total 3078
telemt_desync_frames_bucket_total{bucket="1_2"} 921
telemt_desync_frames_bucket_total{bucket="3_10"} 1904
telemt_desync_frames_bucket_total{bucket="gt_10"} 1900
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 21959
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20309
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1632
telemt_user_connections_total{user="hello"} 1474294
telemt_user_connections_current{user="hello"} 2296
telemt_user_octets_from_client{user="hello"} 20865127485 (19.43 GB)
telemt_user_octets_to_client{user="hello"} 573017722910 (533.66 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 691
telemt_user_unique_ips_recent_window{user="hello"} 308
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 128251.4 (35h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1183942
telemt_connections_bad_total 77964
telemt_handshake_timeouts_total 30890
telemt_upstream_connect_attempt_total 29122
telemt_upstream_connect_success_total 28958
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 29122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 43237
telemt_me_reconnect_success_total 22530
telemt_me_reader_eof_total 24480
telemt_me_idle_close_by_peer_total 24473
telemt_me_route_drop_no_conn_total 402338
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 900583
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3122
telemt_desync_full_logged_total 1010
telemt_desync_suppressed_total 2112
telemt_desync_frames_bucket_total{bucket="1_2"} 828
telemt_desync_frames_bucket_total{bucket="3_10"} 1213
telemt_desync_frames_bucket_total{bucket="gt_10"} 1081
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 23481
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22518
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 951
telemt_user_connections_total{user="hello"} 898663
telemt_user_connections_current{user="hello"} 1545
telemt_user_octets_from_client{user="hello"} 47190210496 (43.95 GB)
telemt_user_octets_to_client{user="hello"} 439027536424 (408.88 GB)
telemt_user_unique_ips_current{user="hello"} 452
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 128310.8 (35h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1581401
telemt_connections_bad_total 79155
telemt_handshake_timeouts_total 27730
telemt_upstream_connect_attempt_total 92193
telemt_upstream_connect_success_total 89741
telemt_upstream_connect_fail_total 2452
telemt_upstream_connect_attempts_per_request{bucket="1"} 92193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2452
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 39014
telemt_me_reconnect_success_total 18592
telemt_me_reader_eof_total 20384
telemt_me_idle_close_by_peer_total 20381
telemt_me_route_drop_no_conn_total 632986
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1294897
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5044
telemt_desync_full_logged_total 1623
telemt_desync_suppressed_total 3421
telemt_desync_frames_bucket_total{bucket="1_2"} 1193
telemt_desync_frames_bucket_total{bucket="3_10"} 2092
telemt_desync_frames_bucket_total{bucket="gt_10"} 1759
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19573
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18572
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 981
telemt_user_connections_total{user="hello"} 1358158
telemt_user_connections_current{user="hello"} 2127
telemt_user_octets_from_client{user="hello"} 22893243622 (21.32 GB)
telemt_user_octets_to_client{user="hello"} 660718442650 (615.34 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 589
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 128282.5 (35h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1127957
telemt_connections_bad_total 106154
telemt_handshake_timeouts_total 11675
telemt_upstream_connect_attempt_total 49163
telemt_upstream_connect_success_total 48485
telemt_upstream_connect_fail_total 678
telemt_upstream_connect_attempts_per_request{bucket="1"} 49163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 426
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 678
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60595
telemt_me_reconnect_success_total 25625
telemt_me_reader_eof_total 27703
telemt_me_idle_close_by_peer_total 27700
telemt_me_route_drop_no_conn_total 362733
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 928593
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4019
telemt_desync_full_logged_total 1233
telemt_desync_suppressed_total 2786
telemt_desync_frames_bucket_total{bucket="1_2"} 1118
telemt_desync_frames_bucket_total{bucket="3_10"} 1551
telemt_desync_frames_bucket_total{bucket="gt_10"} 1350
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27112
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25617
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1487
telemt_user_connections_total{user="hello"} 945029
telemt_user_connections_current{user="hello"} 1755
telemt_user_octets_from_client{user="hello"} 17607331720 (16.40 GB)
telemt_user_octets_to_client{user="hello"} 475918077496 (443.23 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 128443.6 (35h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1239668
telemt_connections_bad_total 128456
telemt_handshake_timeouts_total 10709
telemt_upstream_connect_attempt_total 25468
telemt_upstream_connect_success_total 25317
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 25468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 151
telemt_me_reconnect_attempts_total 30244
telemt_me_reconnect_success_total 18947
telemt_me_reader_eof_total 20523
telemt_me_idle_close_by_peer_total 20521
telemt_me_route_drop_no_conn_total 836917
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1216093
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2341
telemt_desync_full_logged_total 824
telemt_desync_suppressed_total 1517
telemt_desync_frames_bucket_total{bucket="1_2"} 520
telemt_desync_frames_bucket_total{bucket="3_10"} 897
telemt_desync_frames_bucket_total{bucket="gt_10"} 924
telemt_pool_swap_total 117
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19590
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18933
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 643
telemt_user_connections_total{user="hello"} 1024759
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 16230860368 (15.12 GB)
telemt_user_octets_to_client{user="hello"} 456492795764 (425.14 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 76210.6 (21h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619856
telemt_connections_bad_total 57649
telemt_handshake_timeouts_total 14064
telemt_upstream_connect_attempt_total 26057
telemt_upstream_connect_success_total 25785
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 26057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 33470
telemt_me_reconnect_success_total 21854
telemt_me_reader_eof_total 23095
telemt_me_idle_close_by_peer_total 23095
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 154482
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 457737
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2021
telemt_desync_full_logged_total 678
telemt_desync_suppressed_total 1343
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 895
telemt_desync_frames_bucket_total{bucket="gt_10"} 792
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22451
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21809
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 597
telemt_user_connections_total{user="hello"} 457492
telemt_user_connections_current{user="hello"} 1150
telemt_user_octets_from_client{user="hello"} 27230265473 (25.36 GB)
telemt_user_octets_to_client{user="hello"} 353582381558 (329.30 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 382
telemt_user_unique_ips_recent_window{user="hello"} 167
```