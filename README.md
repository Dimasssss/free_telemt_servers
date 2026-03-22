# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 21:11:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 86717.9 (24h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3186496
telemt_connections_bad_total 229353
telemt_connections_current 849
telemt_connections_me_current 849
telemt_handshake_timeouts_total 101851
telemt_upstream_connect_attempt_total 31805
telemt_upstream_connect_success_total 31804
telemt_upstream_connect_attempts_per_request{bucket="1"} 31804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1283
telemt_me_reconnect_success_total 530
telemt_me_reader_eof_total 540
telemt_me_idle_close_by_peer_total 540
telemt_me_route_drop_no_conn_total 2828628
telemt_me_route_drop_channel_closed_total 1137
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2685449
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 588
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 672
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 11584
telemt_desync_full_logged_total 3637
telemt_desync_suppressed_total 7947
telemt_desync_frames_bucket_total{bucket="1_2"} 3131
telemt_desync_frames_bucket_total{bucket="3_10"} 4242
telemt_desync_frames_bucket_total{bucket="gt_10"} 4211
telemt_pool_swap_total 96
telemt_pool_force_close_total 2993
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 604
telemt_me_draining_writers_reap_progress_total 29092
telemt_me_writer_removed_unexpected_total 524
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2118
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27203
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2938
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26099
telemt_me_writer_teardown_success_total{mode="normal"} 29321
telemt_me_writer_teardown_noop_total 29103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58424
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 332.416478
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58424
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 604
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 471
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 2675883
telemt_user_connections_current{user="hello"} 849
telemt_user_octets_from_client{user="hello"} 39068422404 (36.39 GB)
telemt_user_octets_to_client{user="hello"} 720000761244 (670.55 GB)
telemt_user_unique_ips_current{user="hello"} 396
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 100083.9 (27h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3891587
telemt_connections_bad_total 344521
telemt_connections_current 819
telemt_connections_me_current 819
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 98876
telemt_upstream_connect_attempt_total 60087
telemt_upstream_connect_success_total 59353
telemt_upstream_connect_fail_total 648
telemt_upstream_connect_attempts_per_request{bucket="1"} 60001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 648
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6906
telemt_me_reconnect_success_total 2694
telemt_me_reader_eof_total 2641
telemt_me_idle_close_by_peer_total 2641
telemt_me_route_drop_no_conn_total 3622745
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3102439
telemt_me_endpoint_quarantine_total 760
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 772
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 12558
telemt_desync_full_logged_total 7034
telemt_desync_suppressed_total 5524
telemt_desync_frames_bucket_total{bucket="1_2"} 2841
telemt_desync_frames_bucket_total{bucket="3_10"} 4930
telemt_desync_frames_bucket_total{bucket="gt_10"} 4787
telemt_pool_swap_total 94
telemt_pool_force_close_total 2827
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 234
telemt_me_draining_writers_reap_progress_total 39835
telemt_me_writer_removed_unexpected_total 2584
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4863
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37576
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2400
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37008
telemt_me_writer_teardown_success_total{mode="normal"} 42439
telemt_me_writer_teardown_noop_total 39836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82275
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.363648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82275
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 234
telemt_me_refill_failed_total 168
telemt_me_writer_restored_same_endpoint_total 2373
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 3113138
telemt_user_connections_current{user="hello"} 819
telemt_user_octets_from_client{user="hello"} 40867740579 (38.06 GB)
telemt_user_octets_to_client{user="hello"} 757788570926 (705.75 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 174944.3 (48h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16067603
telemt_connections_bad_total 1556825
telemt_connections_current 1352
telemt_connections_me_current 1352
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 394585
telemt_upstream_connect_attempt_total 77598
telemt_upstream_connect_success_total 77498
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 77515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37300
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2841
telemt_me_reconnect_success_total 1476
telemt_me_reader_eof_total 1421
telemt_me_idle_close_by_peer_total 1419
telemt_me_route_drop_no_conn_total 14008317
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12808219
telemt_me_endpoint_quarantine_total 1114
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1306
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 52874
telemt_desync_full_logged_total 16691
telemt_desync_suppressed_total 36183
telemt_desync_frames_bucket_total{bucket="1_2"} 11765
telemt_desync_frames_bucket_total{bucket="3_10"} 20601
telemt_desync_frames_bucket_total{bucket="gt_10"} 20508
telemt_pool_swap_total 189
telemt_pool_force_close_total 6356
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1024
telemt_me_draining_writers_reap_progress_total 57599
telemt_me_writer_removed_unexpected_total 1371
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5047
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53202
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5886
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51243
telemt_me_writer_teardown_success_total{mode="normal"} 58249
telemt_me_writer_teardown_noop_total 57650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115899
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 314.754705
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115899
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1024
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1275
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12808545
telemt_user_connections_current{user="hello"} 1352
telemt_user_octets_from_client{user="hello"} 188308094761 (175.38 GB)
telemt_user_octets_to_client{user="hello"} 3428232092583 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 542
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 174945.6 (48h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11649136
telemt_connections_bad_total 1175648
telemt_connections_current 1080
telemt_connections_me_current 1080
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343411
telemt_upstream_connect_attempt_total 92153
telemt_upstream_connect_success_total 90855
telemt_upstream_connect_fail_total 857
telemt_upstream_connect_attempts_per_request{bucket="1"} 91712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37345
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3790
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 857
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4277
telemt_me_reconnect_success_total 1785
telemt_me_reader_eof_total 1643
telemt_me_idle_close_by_peer_total 1643
telemt_me_route_drop_no_conn_total 4526608
telemt_me_route_drop_channel_closed_total 496
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8677135
telemt_me_endpoint_quarantine_total 1114
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1327
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 38390
telemt_desync_full_logged_total 12916
telemt_desync_suppressed_total 25474
telemt_desync_frames_bucket_total{bucket="1_2"} 9483
telemt_desync_frames_bucket_total{bucket="3_10"} 14769
telemt_desync_frames_bucket_total{bucket="gt_10"} 14138
telemt_pool_swap_total 186
telemt_pool_force_close_total 5729
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 705
telemt_me_draining_writers_reap_progress_total 56032
telemt_me_writer_removed_unexpected_total 1681
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5200
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52361
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5217
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50303
telemt_me_writer_teardown_success_total{mode="normal"} 57561
telemt_me_writer_teardown_noop_total 56057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113618
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.152045
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113618
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 705
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1518
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8615065
telemt_user_connections_current{user="hello"} 1080
telemt_user_octets_from_client{user="hello"} 216560173412 (201.69 GB)
telemt_user_octets_to_client{user="hello"} 3898953164743 (3.55 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 174910.0 (48h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10902037
telemt_connections_bad_total 945486
telemt_connections_current 718
telemt_connections_me_current 718
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344560
telemt_upstream_connect_attempt_total 75785
telemt_upstream_connect_success_total 74421
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 74618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35703
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 5359
telemt_me_reconnect_success_total 2179
telemt_me_reader_eof_total 1913
telemt_me_idle_close_by_peer_total 1912
telemt_me_route_drop_no_conn_total 5306947
telemt_me_route_drop_channel_closed_total 382
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8250038
telemt_me_endpoint_quarantine_total 1204
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1281
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 37815
telemt_desync_full_logged_total 12525
telemt_desync_suppressed_total 25290
telemt_desync_frames_bucket_total{bucket="1_2"} 9554
telemt_desync_frames_bucket_total{bucket="3_10"} 14461
telemt_desync_frames_bucket_total{bucket="gt_10"} 13800
telemt_pool_swap_total 183
telemt_pool_force_close_total 5667
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 722
telemt_me_draining_writers_reap_progress_total 56209
telemt_me_writer_removed_unexpected_total 2064
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5780
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52417
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5102
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50542
telemt_me_writer_teardown_success_total{mode="normal"} 58197
telemt_me_writer_teardown_noop_total 56280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114477
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.205467
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114477
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 722
telemt_me_refill_failed_total 168
telemt_me_writer_restored_same_endpoint_total 1880
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 8242070
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 191710662153 (178.54 GB)
telemt_user_octets_to_client{user="hello"} 3428594303709 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 45188.5 (12h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10963148
telemt_connections_bad_total 665302
telemt_connections_current 1483
telemt_connections_me_current 1483
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 242711
telemt_upstream_connect_attempt_total 49835
telemt_upstream_connect_success_total 47315
telemt_upstream_connect_fail_total 1730
telemt_upstream_connect_attempts_per_request{bucket="1"} 49045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5982
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1730
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6968
telemt_me_reconnect_success_total 1016
telemt_me_reader_eof_total 625
telemt_me_idle_close_by_peer_total 624
telemt_me_route_drop_no_conn_total 25238003
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9103901
telemt_me_endpoint_quarantine_total 314
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 357
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 15154
telemt_desync_full_logged_total 4033
telemt_desync_suppressed_total 11121
telemt_desync_frames_bucket_total{bucket="1_2"} 2839
telemt_desync_frames_bucket_total{bucket="3_10"} 6142
telemt_desync_frames_bucket_total{bucket="gt_10"} 6173
telemt_pool_swap_total 46
telemt_pool_force_close_total 1612
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 445
telemt_me_draining_writers_reap_progress_total 13074
telemt_me_writer_removed_unexpected_total 905
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1966
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11968
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1306
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11462
telemt_me_writer_teardown_success_total{mode="normal"} 13934
telemt_me_writer_teardown_noop_total 13093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27027
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.085574
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27027
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 445
telemt_me_refill_failed_total 324
telemt_me_writer_restored_same_endpoint_total 661
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 9128663
telemt_user_connections_current{user="hello"} 1483
telemt_user_octets_from_client{user="hello"} 84802343160 (78.98 GB)
telemt_user_octets_to_client{user="hello"} 533962743438 (497.29 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 174915.2 (48h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10801609
telemt_connections_bad_total 909946
telemt_connections_current 964
telemt_connections_me_current 964
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 237547
telemt_upstream_connect_attempt_total 104691
telemt_upstream_connect_success_total 103594
telemt_upstream_connect_fail_total 936
telemt_upstream_connect_attempts_per_request{bucket="1"} 104530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1349
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 936
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72454
telemt_me_reconnect_success_total 2857
telemt_me_reader_eof_total 2552
telemt_me_idle_close_by_peer_total 2550
telemt_me_route_drop_no_conn_total 5225082
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8537271
telemt_me_endpoint_quarantine_total 1155
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1309
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 45516
telemt_desync_full_logged_total 15534
telemt_desync_suppressed_total 29982
telemt_desync_frames_bucket_total{bucket="1_2"} 9235
telemt_desync_frames_bucket_total{bucket="3_10"} 17429
telemt_desync_frames_bucket_total{bucket="gt_10"} 18852
telemt_pool_swap_total 179
telemt_pool_force_close_total 5346
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 645
telemt_me_draining_writers_reap_progress_total 60060
telemt_me_writer_removed_unexpected_total 2587
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6344
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56332
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4616
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54714
telemt_me_writer_teardown_success_total{mode="normal"} 62676
telemt_me_writer_teardown_noop_total 60061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122737
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.115601
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122737
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 645
telemt_me_refill_failed_total 4287
telemt_me_writer_restored_same_endpoint_total 2406
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8540407
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 193122762637 (179.86 GB)
telemt_user_octets_to_client{user="hello"} 3255743581860 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 111751.3 (31h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11415646
telemt_connections_bad_total 456593
telemt_connections_current 1241
telemt_connections_me_current 1241
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4679732
telemt_upstream_connect_attempt_total 52843
telemt_upstream_connect_success_total 52448
telemt_upstream_connect_fail_total 385
telemt_upstream_connect_attempts_per_request{bucket="1"} 52833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 385
telemt_me_reconnect_attempts_total 48656
telemt_me_reconnect_success_total 1697
telemt_me_reader_eof_total 1357
telemt_me_idle_close_by_peer_total 1356
telemt_me_route_drop_no_conn_total 4057759
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5506131
telemt_me_endpoint_quarantine_total 725
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 842
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30943
telemt_desync_full_logged_total 10516
telemt_desync_suppressed_total 20427
telemt_desync_frames_bucket_total{bucket="1_2"} 6144
telemt_desync_frames_bucket_total{bucket="3_10"} 12243
telemt_desync_frames_bucket_total{bucket="gt_10"} 12556
telemt_pool_swap_total 118
telemt_pool_force_close_total 3562
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 39046
telemt_me_writer_removed_unexpected_total 1416
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3413
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37084
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3121
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35484
telemt_me_writer_teardown_success_total{mode="normal"} 40497
telemt_me_writer_teardown_noop_total 39053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79550
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.612106
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79550
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1507
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5498857
telemt_user_connections_current{user="hello"} 1241
telemt_user_octets_from_client{user="hello"} 117898268760 (109.80 GB)
telemt_user_octets_to_client{user="hello"} 2109166302526 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 92722.1 (25h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1404914
telemt_connections_bad_total 34402
telemt_connections_current 781
telemt_connections_me_current 781
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 26008
telemt_upstream_connect_attempt_total 43519
telemt_upstream_connect_success_total 43383
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 43492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 742
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2044
telemt_me_reconnect_success_total 831
telemt_me_reader_eof_total 813
telemt_me_idle_close_by_peer_total 813
telemt_me_route_drop_no_conn_total 489282
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1246934
telemt_me_endpoint_quarantine_total 754
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 761
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 1
telemt_desync_total 7662
telemt_desync_full_logged_total 2353
telemt_desync_suppressed_total 5309
telemt_desync_frames_bucket_total{bucket="1_2"} 1778
telemt_desync_frames_bucket_total{bucket="3_10"} 2960
telemt_desync_frames_bucket_total{bucket="gt_10"} 2924
telemt_pool_swap_total 99
telemt_pool_force_close_total 2576
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 36324
telemt_me_writer_removed_unexpected_total 783
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2869
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34271
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33748
telemt_me_writer_teardown_success_total{mode="normal"} 37140
telemt_me_writer_teardown_noop_total 36328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73468
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.727315
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73468
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 705
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1242928
telemt_user_connections_current{user="hello"} 781
telemt_user_octets_from_client{user="hello"} 24213728153 (22.55 GB)
telemt_user_octets_to_client{user="hello"} 525812018983 (489.70 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 174920.2 (48h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13139053
telemt_connections_bad_total 1554475
telemt_connections_current 1128
telemt_connections_me_current 1128
telemt_handshake_timeouts_total 376916
telemt_upstream_connect_attempt_total 66444
telemt_upstream_connect_success_total 66111
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 66309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2584
telemt_me_reconnect_success_total 1361
telemt_me_reader_eof_total 1328
telemt_me_idle_close_by_peer_total 1328
telemt_me_route_drop_no_conn_total 4456413
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9931035
telemt_me_endpoint_quarantine_total 1190
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1310
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 41399
telemt_desync_full_logged_total 13488
telemt_desync_suppressed_total 27911
telemt_desync_frames_bucket_total{bucket="1_2"} 9961
telemt_desync_frames_bucket_total{bucket="3_10"} 15243
telemt_desync_frames_bucket_total{bucket="gt_10"} 16195
telemt_pool_swap_total 194
telemt_pool_force_close_total 5313
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 656
telemt_me_draining_writers_reap_progress_total 59907
telemt_me_writer_removed_unexpected_total 1278
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4870
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56355
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54594
telemt_me_writer_teardown_success_total{mode="normal"} 61225
telemt_me_writer_teardown_noop_total 59909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.535333
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 656
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1192
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 9897920
telemt_user_connections_current{user="hello"} 1128
telemt_user_octets_from_client{user="hello"} 193432738872 (180.15 GB)
telemt_user_octets_to_client{user="hello"} 4378645290668 (3.98 TB)
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 174916.7 (48h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11415297
telemt_connections_bad_total 1290682
telemt_connections_current 973
telemt_connections_me_current 973
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 300623
telemt_upstream_connect_attempt_total 92877
telemt_upstream_connect_success_total 92041
telemt_upstream_connect_fail_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 92670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38788
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 629
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9974
telemt_me_reconnect_success_total 2400
telemt_me_reader_eof_total 2244
telemt_me_idle_close_by_peer_total 2243
telemt_me_seq_mismatch_total 80
telemt_me_route_drop_no_conn_total 5616102
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8831974
telemt_me_endpoint_quarantine_total 1340
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1313
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 40685
telemt_desync_full_logged_total 13088
telemt_desync_suppressed_total 27597
telemt_desync_frames_bucket_total{bucket="1_2"} 10295
telemt_desync_frames_bucket_total{bucket="3_10"} 15046
telemt_desync_frames_bucket_total{bucket="gt_10"} 15344
telemt_pool_swap_total 184
telemt_pool_force_close_total 5111
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 643
telemt_me_draining_writers_reap_progress_total 59636
telemt_me_writer_removed_unexpected_total 2275
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6210
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55779
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4640
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54525
telemt_me_writer_teardown_success_total{mode="normal"} 61989
telemt_me_writer_teardown_noop_total 59641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121630
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.250109
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121630
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 643
telemt_me_refill_failed_total 391
telemt_me_writer_restored_same_endpoint_total 1953
telemt_me_writer_restored_fallback_total 111
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 8837446
telemt_user_connections_current{user="hello"} 973
telemt_user_octets_from_client{user="hello"} 156285060133 (145.55 GB)
telemt_user_octets_to_client{user="hello"} 3433080217299 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 396
telemt_user_unique_ips_recent_window{user="hello"} 122
```