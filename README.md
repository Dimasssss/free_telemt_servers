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

# Server Metrics 2026-03-18 04:40:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 122117.4 (33h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1395370
telemt_connections_bad_total 10541
telemt_handshake_timeouts_total 34186
telemt_upstream_connect_attempt_total 26799
telemt_upstream_connect_success_total 26286
telemt_upstream_connect_fail_total 513
telemt_upstream_connect_attempts_per_request{bucket="1"} 26799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 513
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 35071
telemt_me_reconnect_success_total 17924
telemt_me_reader_eof_total 19443
telemt_me_idle_close_by_peer_total 19442
telemt_me_route_drop_no_conn_total 595778
telemt_me_route_drop_channel_closed_total 163
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1283889
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7982
telemt_desync_full_logged_total 2388
telemt_desync_suppressed_total 5594
telemt_desync_frames_bucket_total{bucket="1_2"} 2107
telemt_desync_frames_bucket_total{bucket="3_10"} 3059
telemt_desync_frames_bucket_total{bucket="gt_10"} 2816
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 18725
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17902
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 801
telemt_user_connections_total{user="hello"} 1278103
telemt_user_connections_current{user="hello"} 823
telemt_user_octets_from_client{user="hello"} 25689500195 (23.93 GB)
telemt_user_octets_to_client{user="hello"} 452515188095 (421.44 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 122369.0 (33h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1510743
telemt_connections_bad_total 73743
telemt_handshake_timeouts_total 50191
telemt_upstream_connect_attempt_total 470217
telemt_upstream_connect_success_total 468598
telemt_upstream_connect_fail_total 1619
telemt_upstream_connect_attempts_per_request{bucket="1"} 470217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1619
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126330
telemt_me_reconnect_success_total 19602
telemt_me_reader_eof_total 21862
telemt_me_idle_close_by_peer_total 21849
telemt_me_route_drop_no_conn_total 392642
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 871337
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3897
telemt_desync_full_logged_total 1359
telemt_desync_suppressed_total 2538
telemt_desync_frames_bucket_total{bucket="1_2"} 764
telemt_desync_frames_bucket_total{bucket="3_10"} 1601
telemt_desync_frames_bucket_total{bucket="gt_10"} 1532
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 21223
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19584
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1621
telemt_user_connections_total{user="hello"} 1313655
telemt_user_connections_current{user="hello"} 1308
telemt_user_octets_from_client{user="hello"} 17780538785 (16.56 GB)
telemt_user_octets_to_client{user="hello"} 487368263654 (453.90 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 122145.0 (33h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 945871
telemt_connections_bad_total 66905
telemt_handshake_timeouts_total 27613
telemt_upstream_connect_attempt_total 28169
telemt_upstream_connect_success_total 28009
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 28169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15064
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42591
telemt_me_reconnect_success_total 21892
telemt_me_reader_eof_total 23797
telemt_me_idle_close_by_peer_total 23790
telemt_me_route_drop_no_conn_total 357176
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 782756
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2506
telemt_desync_full_logged_total 831
telemt_desync_suppressed_total 1675
telemt_desync_frames_bucket_total{bucket="1_2"} 707
telemt_desync_frames_bucket_total{bucket="3_10"} 966
telemt_desync_frames_bucket_total{bucket="gt_10"} 833
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 22828
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21880
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 936
telemt_user_connections_total{user="hello"} 780871
telemt_user_connections_current{user="hello"} 855
telemt_user_octets_from_client{user="hello"} 45088291964 (41.99 GB)
telemt_user_octets_to_client{user="hello"} 361755726156 (336.91 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 122204.3 (33h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1405009
telemt_connections_bad_total 68832
telemt_handshake_timeouts_total 24433
telemt_upstream_connect_attempt_total 91178
telemt_upstream_connect_success_total 88741
telemt_upstream_connect_fail_total 2437
telemt_upstream_connect_attempts_per_request{bucket="1"} 91178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14762
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2437
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38312
telemt_me_reconnect_success_total 17902
telemt_me_reader_eof_total 19649
telemt_me_idle_close_by_peer_total 19646
telemt_me_route_drop_no_conn_total 570971
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1142855
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4274
telemt_desync_full_logged_total 1407
telemt_desync_suppressed_total 2867
telemt_desync_frames_bucket_total{bucket="1_2"} 1050
telemt_desync_frames_bucket_total{bucket="3_10"} 1786
telemt_desync_frames_bucket_total{bucket="gt_10"} 1438
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 18868
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17882
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 966
telemt_user_connections_total{user="hello"} 1206161
telemt_user_connections_current{user="hello"} 1151
telemt_user_octets_from_client{user="hello"} 18858611938 (17.56 GB)
telemt_user_octets_to_client{user="hello"} 583159198158 (543.11 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 122176.1 (33h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 969811
telemt_connections_bad_total 102676
telemt_handshake_timeouts_total 9056
telemt_upstream_connect_attempt_total 48084
telemt_upstream_connect_success_total 47423
telemt_upstream_connect_fail_total 661
telemt_upstream_connect_attempts_per_request{bucket="1"} 48084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 661
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59836
telemt_me_reconnect_success_total 24870
telemt_me_reader_eof_total 26913
telemt_me_idle_close_by_peer_total 26910
telemt_me_route_drop_no_conn_total 309819
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 789448
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3527
telemt_desync_full_logged_total 1069
telemt_desync_suppressed_total 2458
telemt_desync_frames_bucket_total{bucket="1_2"} 1058
telemt_desync_frames_bucket_total{bucket="3_10"} 1386
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 64
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26346
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24862
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1476
telemt_user_connections_total{user="hello"} 805926
telemt_user_connections_current{user="hello"} 1061
telemt_user_octets_from_client{user="hello"} 15445157224 (14.38 GB)
telemt_user_octets_to_client{user="hello"} 409927973372 (381.78 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 122337.5 (33h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1177633
telemt_connections_bad_total 126992
telemt_handshake_timeouts_total 10355
telemt_upstream_connect_attempt_total 24342
telemt_upstream_connect_success_total 24203
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 24342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29432
telemt_me_reconnect_success_total 18138
telemt_me_reader_eof_total 19661
telemt_me_idle_close_by_peer_total 19659
telemt_me_route_drop_no_conn_total 813378
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1159234
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2168
telemt_desync_full_logged_total 762
telemt_desync_suppressed_total 1406
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 821
telemt_desync_frames_bucket_total{bucket="gt_10"} 869
telemt_pool_swap_total 110
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18774
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18124
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 967922
telemt_user_connections_current{user="hello"} 643
telemt_user_octets_from_client{user="hello"} 15408523964 (14.35 GB)
telemt_user_octets_to_client{user="hello"} 427067505440 (397.74 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 70104.4 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510361
telemt_connections_bad_total 52833
telemt_handshake_timeouts_total 12856
telemt_upstream_connect_attempt_total 24947
telemt_upstream_connect_success_total 24693
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 24947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32680
telemt_me_reconnect_success_total 21069
telemt_me_reader_eof_total 22262
telemt_me_idle_close_by_peer_total 22262
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 122833
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365241
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1601
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 1076
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 718
telemt_desync_frames_bucket_total{bucket="gt_10"} 614
telemt_pool_swap_total 47
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21657
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21026
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 365032
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 23535454129 (21.92 GB)
telemt_user_octets_to_client{user="hello"} 294884234162 (274.63 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 93
```