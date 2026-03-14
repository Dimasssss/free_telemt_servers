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

# Server Metrics 2026-03-14 08:59:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 177987.0 (49h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 687009
telemt_connections_bad_total 32586
telemt_handshake_timeouts_total 13383
telemt_upstream_connect_attempt_total 45180
telemt_upstream_connect_success_total 44951
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 45180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5784
telemt_me_reconnect_attempts_total 40413
telemt_me_reconnect_success_total 35714
telemt_me_reader_eof_total 38185
telemt_me_idle_close_by_peer_total 38184
telemt_me_route_drop_no_conn_total 227178
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 586947
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2263
telemt_desync_full_logged_total 769
telemt_desync_suppressed_total 1494
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 825
telemt_desync_frames_bucket_total{bucket="gt_10"} 949
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 36241
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35694
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 586830
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 17061587250 (15.89 GB)
telemt_user_octets_to_client{user="hello"} 281586568656 (262.25 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 177880.8 (49h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345608
telemt_connections_bad_total 2787
telemt_handshake_timeouts_total 3032
telemt_upstream_connect_attempt_total 152726
telemt_upstream_connect_success_total 151398
telemt_upstream_connect_fail_total 1328
telemt_upstream_connect_attempts_per_request{bucket="1"} 152726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2439
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1328
telemt_me_keepalive_timeout_total 5340
telemt_me_reconnect_attempts_total 182078
telemt_me_reconnect_success_total 39233
telemt_me_reader_eof_total 44748
telemt_me_idle_close_by_peer_total 44748
telemt_me_route_drop_no_conn_total 116215
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222974
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 44
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
telemt_me_writer_removed_unexpected_total 44074
telemt_me_refill_failed_total 4457
telemt_me_writer_restored_same_endpoint_total 39216
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4841
telemt_user_connections_total{user="hello"} 326080
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 3388874159 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 105099925483 (97.88 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 177844.4 (49h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402983
telemt_connections_bad_total 3199
telemt_handshake_timeouts_total 35598
telemt_upstream_connect_attempt_total 47215
telemt_upstream_connect_success_total 47206
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 47215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25517
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3528
telemt_me_reconnect_attempts_total 39599
telemt_me_reconnect_success_total 38303
telemt_me_reader_eof_total 41164
telemt_me_idle_close_by_peer_total 41164
telemt_me_route_drop_no_conn_total 145733
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349993
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 129
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 38766
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 38282
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 349752
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 13700848272 (12.76 GB)
telemt_user_octets_to_client{user="hello"} 150290006720 (139.97 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 177819.9 (49h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 506402
telemt_connections_bad_total 16443
telemt_handshake_timeouts_total 4624
telemt_upstream_connect_attempt_total 77353
telemt_upstream_connect_success_total 66715
telemt_upstream_connect_fail_total 10638
telemt_upstream_connect_attempts_per_request{bucket="1"} 77353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10638
telemt_me_keepalive_timeout_total 5494
telemt_me_reconnect_attempts_total 149950
telemt_me_reconnect_success_total 38827
telemt_me_reader_eof_total 43547
telemt_me_idle_close_by_peer_total 43539
telemt_me_route_drop_no_conn_total 183531
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 432632
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1906
telemt_desync_full_logged_total 564
telemt_desync_suppressed_total 1342
telemt_desync_frames_bucket_total{bucket="1_2"} 450
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 720
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 42743
telemt_me_refill_failed_total 3465
telemt_me_writer_restored_same_endpoint_total 38817
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3916
telemt_user_connections_total{user="hello"} 451513
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 9748499047 (9.08 GB)
telemt_user_octets_to_client{user="hello"} 188819606992 (175.85 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 127991.5 (35h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210551
telemt_connections_bad_total 32228
telemt_handshake_timeouts_total 1775
telemt_upstream_connect_attempt_total 45099
telemt_upstream_connect_success_total 44662
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 45099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_timeout_total 2583
telemt_me_reconnect_attempts_total 48108
telemt_me_reconnect_success_total 33388
telemt_me_reader_eof_total 35729
telemt_me_idle_close_by_peer_total 35729
telemt_me_route_drop_no_conn_total 63395
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165934
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 718
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 34150
telemt_me_refill_failed_total 456
telemt_me_writer_restored_same_endpoint_total 33370
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 762
telemt_user_connections_total{user="hello"} 170696
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 2501849677 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 81178277147 (75.60 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 177776.2 (49h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1024770
telemt_connections_bad_total 36400
telemt_handshake_timeouts_total 26510
telemt_upstream_connect_attempt_total 37039
telemt_upstream_connect_success_total 36841
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 37039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_timeout_total 4765
telemt_me_reconnect_attempts_total 32733
telemt_me_reconnect_success_total 28050
telemt_me_reader_eof_total 30094
telemt_me_idle_close_by_peer_total 30091
telemt_me_route_drop_no_conn_total 481074
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 949685
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 792
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 533
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 168
telemt_me_writer_removed_unexpected_total 28549
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 28043
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 922312
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 16781603216 (15.63 GB)
telemt_user_octets_to_client{user="hello"} 459763735068 (428.19 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 59
```