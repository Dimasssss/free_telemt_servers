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

# Server Metrics 2026-03-19 12:11:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 51810.2 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1278355
telemt_connections_bad_total 104371
telemt_connections_current 1743
telemt_connections_me_current 1743
telemt_handshake_timeouts_total 45165
telemt_upstream_connect_attempt_total 9959
telemt_upstream_connect_success_total 9790
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 9959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 9072
telemt_me_reconnect_success_total 7180
telemt_me_reader_eof_total 7591
telemt_me_idle_close_by_peer_total 7588
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 533230
telemt_me_route_drop_channel_closed_total 222
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1005689
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5563
telemt_desync_full_logged_total 1708
telemt_desync_suppressed_total 3855
telemt_desync_frames_bucket_total{bucket="1_2"} 1770
telemt_desync_frames_bucket_total{bucket="3_10"} 2013
telemt_desync_frames_bucket_total{bucket="gt_10"} 1780
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 7342
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 7159
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 999566
telemt_user_connections_current{user="hello"} 1743
telemt_user_octets_from_client{user="hello"} 15621752472 (14.55 GB)
telemt_user_octets_to_client{user="hello"} 301891340816 (281.16 GB)
telemt_user_unique_ips_current{user="hello"} 599
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 51815.1 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3634662
telemt_connections_bad_total 233287
telemt_connections_current 3904
telemt_connections_me_current 3904
telemt_handshake_timeouts_total 63643
telemt_upstream_connect_attempt_total 9688
telemt_upstream_connect_success_total 9506
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 9688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 18221
telemt_me_reconnect_success_total 6859
telemt_me_reader_eof_total 7529
telemt_me_idle_close_by_peer_total 7528
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 3088310
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3066524
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11755
telemt_desync_full_logged_total 3933
telemt_desync_suppressed_total 7822
telemt_desync_frames_bucket_total{bucket="1_2"} 2284
telemt_desync_frames_bucket_total{bucket="3_10"} 4612
telemt_desync_frames_bucket_total{bucket="gt_10"} 4859
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7336
telemt_me_refill_failed_total 354
telemt_me_writer_restored_same_endpoint_total 6836
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 477
telemt_user_connections_total{user="hello"} 3066133
telemt_user_connections_current{user="hello"} 3904
telemt_user_octets_from_client{user="hello"} 38276823060 (35.65 GB)
telemt_user_octets_to_client{user="hello"} 866675487772 (807.15 GB)
telemt_user_unique_ips_current{user="hello"} 1301
telemt_user_unique_ips_recent_window{user="hello"} 605
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 51812.8 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2732148
telemt_connections_bad_total 317341
telemt_connections_current 3067
telemt_connections_me_current 3067
telemt_handshake_timeouts_total 53437
telemt_upstream_connect_attempt_total 9417
telemt_upstream_connect_success_total 9417
telemt_upstream_connect_attempts_per_request{bucket="1"} 9417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 9124
telemt_me_reconnect_success_total 6770
telemt_me_reader_eof_total 7204
telemt_me_idle_close_by_peer_total 7202
telemt_me_route_drop_no_conn_total 1752149
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2157656
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8845
telemt_desync_full_logged_total 2787
telemt_desync_suppressed_total 6058
telemt_desync_frames_bucket_total{bucket="1_2"} 2029
telemt_desync_frames_bucket_total{bucket="3_10"} 3231
telemt_desync_frames_bucket_total{bucket="gt_10"} 3585
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6957
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 6754
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 2155280
telemt_user_connections_current{user="hello"} 3067
telemt_user_octets_from_client{user="hello"} 29297485424 (27.29 GB)
telemt_user_octets_to_client{user="hello"} 901708353272 (839.78 GB)
telemt_user_unique_ips_current{user="hello"} 1084
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 51865.5 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2764004
telemt_connections_bad_total 142919
telemt_connections_current 2978
telemt_connections_me_current 2978
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 67045
telemt_upstream_connect_attempt_total 24555
telemt_upstream_connect_success_total 24033
telemt_upstream_connect_fail_total 522
telemt_upstream_connect_attempts_per_request{bucket="1"} 24555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5766
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 522
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 11523
telemt_me_reconnect_success_total 6708
telemt_me_reader_eof_total 7132
telemt_me_idle_close_by_peer_total 7131
telemt_me_route_drop_no_conn_total 1795721
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2147317
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7625
telemt_desync_full_logged_total 2534
telemt_desync_suppressed_total 5091
telemt_desync_frames_bucket_total{bucket="1_2"} 1595
telemt_desync_frames_bucket_total{bucket="3_10"} 3012
telemt_desync_frames_bucket_total{bucket="gt_10"} 3018
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7330
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6684
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 2159916
telemt_user_connections_current{user="hello"} 2978
telemt_user_octets_from_client{user="hello"} 24221694180 (22.56 GB)
telemt_user_octets_to_client{user="hello"} 574425012333 (534.97 GB)
telemt_user_msgs_from_client{user="hello"} 46376
telemt_user_msgs_to_client{user="hello"} 105213
telemt_user_unique_ips_current{user="hello"} 993
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 51808.8 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3374726
telemt_connections_bad_total 713980
telemt_connections_current 3951
telemt_connections_me_current 3951
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 65494
telemt_upstream_connect_attempt_total 61066
telemt_upstream_connect_success_total 58589
telemt_upstream_connect_fail_total 2477
telemt_upstream_connect_attempts_per_request{bucket="1"} 61066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1011
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2477
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 69865
telemt_me_reconnect_success_total 6817
telemt_me_reader_eof_total 7139
telemt_me_idle_close_by_peer_total 7136
telemt_me_route_drop_no_conn_total 1448826
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2215291
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9314
telemt_desync_full_logged_total 2904
telemt_desync_suppressed_total 6410
telemt_desync_frames_bucket_total{bucket="1_2"} 1759
telemt_desync_frames_bucket_total{bucket="3_10"} 4003
telemt_desync_frames_bucket_total{bucket="gt_10"} 3552
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 6907
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 6793
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 2264283
telemt_user_connections_current{user="hello"} 3951
telemt_user_octets_from_client{user="hello"} 36615287331 (34.10 GB)
telemt_user_octets_to_client{user="hello"} 843566009020 (785.63 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1222
telemt_user_unique_ips_recent_window{user="hello"} 790
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 51820.8 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 562221
telemt_connections_bad_total 19245
telemt_connections_current 1092
telemt_connections_me_current 1092
telemt_handshake_timeouts_total 4374
telemt_upstream_connect_attempt_total 12816
telemt_upstream_connect_success_total 12480
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 12816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 17448
telemt_me_reconnect_success_total 9855
telemt_me_reader_eof_total 10494
telemt_me_idle_close_by_peer_total 10494
telemt_me_route_drop_no_conn_total 292499
telemt_me_route_drop_channel_closed_total 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511389
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1222
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 797
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 504
telemt_desync_frames_bucket_total{bucket="gt_10"} 480
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 10184
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9824
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 511321
telemt_user_connections_current{user="hello"} 1092
telemt_user_octets_from_client{user="hello"} 8301415060 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 184526759796 (171.85 GB)
telemt_user_unique_ips_current{user="hello"} 369
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 51811.2 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2265965
telemt_connections_bad_total 182557
telemt_connections_current 3062
telemt_connections_me_current 3062
telemt_handshake_timeouts_total 73871
telemt_upstream_connect_attempt_total 10476
telemt_upstream_connect_success_total 10475
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 10325
telemt_me_reconnect_success_total 7833
telemt_me_reader_eof_total 8307
telemt_me_idle_close_by_peer_total 8306
telemt_me_route_drop_no_conn_total 1169721
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1904335
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10374
telemt_desync_full_logged_total 3306
telemt_desync_suppressed_total 7068
telemt_desync_frames_bucket_total{bucket="1_2"} 1984
telemt_desync_frames_bucket_total{bucket="3_10"} 3937
telemt_desync_frames_bucket_total{bucket="gt_10"} 4453
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8011
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 7818
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 1903085
telemt_user_connections_current{user="hello"} 3062
telemt_user_octets_from_client{user="hello"} 24783036948 (23.08 GB)
telemt_user_octets_to_client{user="hello"} 841638902444 (783.84 GB)
telemt_user_unique_ips_current{user="hello"} 1031
telemt_user_unique_ips_recent_window{user="hello"} 436
```