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

# Server Metrics 2026-03-19 12:27:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 52730.0 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1312820
telemt_connections_bad_total 105306
telemt_connections_current 1697
telemt_connections_me_current 1697
telemt_handshake_timeouts_total 46724
telemt_upstream_connect_attempt_total 10137
telemt_upstream_connect_success_total 9966
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 10137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 9205
telemt_me_reconnect_success_total 7311
telemt_me_reader_eof_total 7734
telemt_me_idle_close_by_peer_total 7731
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 545028
telemt_me_route_drop_channel_closed_total 241
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1036365
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5715
telemt_desync_full_logged_total 1764
telemt_desync_suppressed_total 3951
telemt_desync_frames_bucket_total{bucket="1_2"} 1811
telemt_desync_frames_bucket_total{bucket="3_10"} 2053
telemt_desync_frames_bucket_total{bucket="gt_10"} 1851
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 7477
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 7289
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 1030142
telemt_user_connections_current{user="hello"} 1697
telemt_user_octets_from_client{user="hello"} 16114602400 (15.01 GB)
telemt_user_octets_to_client{user="hello"} 312223798788 (290.78 GB)
telemt_user_unique_ips_current{user="hello"} 589
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 52734.2 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3733531
telemt_connections_bad_total 239852
telemt_connections_current 3900
telemt_connections_me_current 3900
telemt_handshake_timeouts_total 64334
telemt_upstream_connect_attempt_total 9821
telemt_upstream_connect_success_total 9637
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 9821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 18357
telemt_me_reconnect_success_total 6946
telemt_me_reader_eof_total 7617
telemt_me_idle_close_by_peer_total 7616
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 3141027
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3149981
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11999
telemt_desync_full_logged_total 4013
telemt_desync_suppressed_total 7986
telemt_desync_frames_bucket_total{bucket="1_2"} 2322
telemt_desync_frames_bucket_total{bucket="3_10"} 4690
telemt_desync_frames_bucket_total{bucket="gt_10"} 4987
telemt_pool_swap_total 34
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7425
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 6921
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 479
telemt_user_connections_total{user="hello"} 3149584
telemt_user_connections_current{user="hello"} 3900
telemt_user_octets_from_client{user="hello"} 39168525028 (36.48 GB)
telemt_user_octets_to_client{user="hello"} 894982067552 (833.52 GB)
telemt_user_unique_ips_current{user="hello"} 1285
telemt_user_unique_ips_recent_window{user="hello"} 601
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 52731.2 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2798748
telemt_connections_bad_total 319734
telemt_connections_current 3015
telemt_connections_me_current 3015
telemt_handshake_timeouts_total 54154
telemt_upstream_connect_attempt_total 9575
telemt_upstream_connect_success_total 9575
telemt_upstream_connect_attempts_per_request{bucket="1"} 9575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4572
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 9270
telemt_me_reconnect_success_total 6884
telemt_me_reader_eof_total 7327
telemt_me_idle_close_by_peer_total 7325
telemt_me_route_drop_no_conn_total 1778264
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2216615
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9214
telemt_desync_full_logged_total 2889
telemt_desync_suppressed_total 6325
telemt_desync_frames_bucket_total{bucket="1_2"} 2147
telemt_desync_frames_bucket_total{bucket="3_10"} 3355
telemt_desync_frames_bucket_total{bucket="gt_10"} 3712
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7074
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 6868
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 2214208
telemt_user_connections_current{user="hello"} 3015
telemt_user_octets_from_client{user="hello"} 29917495200 (27.86 GB)
telemt_user_octets_to_client{user="hello"} 922932954744 (859.55 GB)
telemt_user_unique_ips_current{user="hello"} 1076
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 52784.1 (14h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2896211
telemt_connections_bad_total 145425
telemt_connections_current 3427
telemt_connections_me_current 3427
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 68101
telemt_upstream_connect_attempt_total 24678
telemt_upstream_connect_success_total 24154
telemt_upstream_connect_fail_total 524
telemt_upstream_connect_attempts_per_request{bucket="1"} 24678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 434
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 524
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 11602
telemt_me_reconnect_success_total 6786
telemt_me_reader_eof_total 7207
telemt_me_idle_close_by_peer_total 7206
telemt_me_route_drop_no_conn_total 2084418
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2271751
telemt_me_writer_pick_total{mode="p2c",result="full"} 113
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_writer_pick_blocking_fallback_total 103
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7812
telemt_desync_full_logged_total 2597
telemt_desync_suppressed_total 5215
telemt_desync_frames_bucket_total{bucket="1_2"} 1657
telemt_desync_frames_bucket_total{bucket="3_10"} 3074
telemt_desync_frames_bucket_total{bucket="gt_10"} 3081
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7402
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6762
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 311
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 2284253
telemt_user_connections_current{user="hello"} 3427
telemt_user_octets_from_client{user="hello"} 24998007160 (23.28 GB)
telemt_user_octets_to_client{user="hello"} 584992481301 (544.82 GB)
telemt_user_msgs_from_client{user="hello"} 46376
telemt_user_msgs_to_client{user="hello"} 105213
telemt_user_unique_ips_current{user="hello"} 1073
telemt_user_unique_ips_recent_window{user="hello"} 649
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 52727.6 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3477583
telemt_connections_bad_total 716885
telemt_connections_current 3699
telemt_connections_me_current 3699
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 67663
telemt_upstream_connect_attempt_total 61257
telemt_upstream_connect_success_total 58778
telemt_upstream_connect_fail_total 2479
telemt_upstream_connect_attempts_per_request{bucket="1"} 61257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6723
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2479
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70011
telemt_me_reconnect_success_total 6962
telemt_me_reader_eof_total 7272
telemt_me_idle_close_by_peer_total 7269
telemt_me_route_drop_no_conn_total 1556141
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2302243
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
telemt_desync_total 9734
telemt_desync_full_logged_total 3023
telemt_desync_suppressed_total 6711
telemt_desync_frames_bucket_total{bucket="1_2"} 1803
telemt_desync_frames_bucket_total{bucket="3_10"} 4196
telemt_desync_frames_bucket_total{bucket="gt_10"} 3735
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 7078
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 6938
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 2351133
telemt_user_connections_current{user="hello"} 3699
telemt_user_octets_from_client{user="hello"} 37494664011 (34.92 GB)
telemt_user_octets_to_client{user="hello"} 864501328304 (805.13 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1107
telemt_user_unique_ips_recent_window{user="hello"} 541
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 52739.7 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 580614
telemt_connections_bad_total 20139
telemt_connections_current 1062
telemt_connections_me_current 1062
telemt_handshake_timeouts_total 4786
telemt_upstream_connect_attempt_total 13034
telemt_upstream_connect_success_total 12689
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 13034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 17614
telemt_me_reconnect_success_total 10021
telemt_me_reader_eof_total 10674
telemt_me_idle_close_by_peer_total 10674
telemt_me_route_drop_no_conn_total 300903
telemt_me_route_drop_channel_closed_total 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 527829
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1323
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 864
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 544
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 10351
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9990
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 527759
telemt_user_connections_current{user="hello"} 1062
telemt_user_octets_from_client{user="hello"} 8440351512 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 188383518020 (175.45 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 52730.1 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2323365
telemt_connections_bad_total 185101
telemt_connections_current 3051
telemt_connections_me_current 3051
telemt_handshake_timeouts_total 74806
telemt_upstream_connect_attempt_total 10650
telemt_upstream_connect_success_total 10649
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 10471
telemt_me_reconnect_success_total 7963
telemt_me_reader_eof_total 8449
telemt_me_idle_close_by_peer_total 8448
telemt_me_route_drop_no_conn_total 1192984
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1956598
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10697
telemt_desync_full_logged_total 3386
telemt_desync_suppressed_total 7311
telemt_desync_frames_bucket_total{bucket="1_2"} 2056
telemt_desync_frames_bucket_total{bucket="3_10"} 4054
telemt_desync_frames_bucket_total{bucket="gt_10"} 4587
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8142
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 7948
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 1955338
telemt_user_connections_current{user="hello"} 3051
telemt_user_octets_from_client{user="hello"} 25494987328 (23.74 GB)
telemt_user_octets_to_client{user="hello"} 863335975696 (804.04 GB)
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 439
```