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

# Server Metrics 2026-03-22 22:02:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 89776.8 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3281464
telemt_connections_bad_total 243216
telemt_connections_current 868
telemt_connections_me_current 868
telemt_handshake_timeouts_total 103932
telemt_upstream_connect_attempt_total 32944
telemt_upstream_connect_success_total 32943
telemt_upstream_connect_attempts_per_request{bucket="1"} 32943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21484
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1317
telemt_me_reconnect_success_total 546
telemt_me_reader_eof_total 559
telemt_me_idle_close_by_peer_total 559
telemt_me_route_drop_no_conn_total 2956999
telemt_me_route_drop_channel_closed_total 1226
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2762691
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 607
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 697
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
telemt_desync_total 11868
telemt_desync_full_logged_total 3719
telemt_desync_suppressed_total 8149
telemt_desync_frames_bucket_total{bucket="1_2"} 3215
telemt_desync_frames_bucket_total{bucket="3_10"} 4341
telemt_desync_frames_bucket_total{bucket="gt_10"} 4312
telemt_pool_swap_total 99
telemt_pool_force_close_total 3096
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 627
telemt_me_draining_writers_reap_progress_total 30154
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2183
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28178
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3041
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27058
telemt_me_writer_teardown_success_total{mode="normal"} 30361
telemt_me_writer_teardown_noop_total 30165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60526
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.460876
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60526
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 627
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 486
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2752088
telemt_user_connections_current{user="hello"} 868
telemt_user_octets_from_client{user="hello"} 39556864564 (36.84 GB)
telemt_user_octets_to_client{user="hello"} 742738592276 (691.73 GB)
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 103143.0 (28h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3928823
telemt_connections_bad_total 352974
telemt_connections_current 771
telemt_connections_me_current 771
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99590
telemt_upstream_connect_attempt_total 62068
telemt_upstream_connect_success_total 61314
telemt_upstream_connect_fail_total 668
telemt_upstream_connect_attempts_per_request{bucket="1"} 61982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 668
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 7503
telemt_me_reconnect_success_total 2919
telemt_me_reader_eof_total 2881
telemt_me_idle_close_by_peer_total 2881
telemt_me_route_drop_no_conn_total 3630768
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3127854
telemt_me_endpoint_quarantine_total 770
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 797
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_me_writers_active_current 127
telemt_desync_total 12708
telemt_desync_full_logged_total 7124
telemt_desync_suppressed_total 5584
telemt_desync_frames_bucket_total{bucket="1_2"} 2868
telemt_desync_frames_bucket_total{bucket="3_10"} 4990
telemt_desync_frames_bucket_total{bucket="gt_10"} 4850
telemt_pool_swap_total 95
telemt_pool_force_close_total 2879
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 41429
telemt_me_writer_removed_unexpected_total 2820
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39112
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38550
telemt_me_writer_teardown_success_total{mode="normal"} 44273
telemt_me_writer_teardown_noop_total 41430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85703
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.407688
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85703
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2593
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 3138517
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 41997667471 (39.11 GB)
telemt_user_octets_to_client{user="hello"} 772245329286 (719.21 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 467
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 178003.0 (49h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16151630
telemt_connections_bad_total 1584443
telemt_connections_current 1055
telemt_connections_me_current 1055
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 395817
telemt_upstream_connect_attempt_total 78952
telemt_upstream_connect_success_total 78852
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 78869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1697
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2856
telemt_me_reconnect_success_total 1488
telemt_me_reader_eof_total 1434
telemt_me_idle_close_by_peer_total 1432
telemt_me_route_drop_no_conn_total 14023049
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12860472
telemt_me_endpoint_quarantine_total 1142
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1329
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 53147
telemt_desync_full_logged_total 16818
telemt_desync_suppressed_total 36329
telemt_desync_frames_bucket_total{bucket="1_2"} 11810
telemt_desync_frames_bucket_total{bucket="3_10"} 20698
telemt_desync_frames_bucket_total{bucket="gt_10"} 20639
telemt_pool_swap_total 192
telemt_pool_force_close_total 6440
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1042
telemt_me_draining_writers_reap_progress_total 58858
telemt_me_writer_removed_unexpected_total 1383
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5135
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54376
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5970
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52418
telemt_me_writer_teardown_success_total{mode="normal"} 59511
telemt_me_writer_teardown_noop_total 58911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118422
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 316.203471
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118422
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1042
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1286
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 12860757
telemt_user_connections_current{user="hello"} 1055
telemt_user_octets_from_client{user="hello"} 189615870577 (176.59 GB)
telemt_user_octets_to_client{user="hello"} 3451185409891 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 459
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 178004.3 (49h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11719962
telemt_connections_bad_total 1197054
telemt_connections_current 906
telemt_connections_me_current 906
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343651
telemt_upstream_connect_attempt_total 93427
telemt_upstream_connect_success_total 92119
telemt_upstream_connect_fail_total 861
telemt_upstream_connect_attempts_per_request{bucket="1"} 92980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3792
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 861
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4309
telemt_me_reconnect_success_total 1801
telemt_me_reader_eof_total 1662
telemt_me_idle_close_by_peer_total 1662
telemt_me_route_drop_no_conn_total 4537451
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8720982
telemt_me_endpoint_quarantine_total 1138
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1351
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_me_writers_active_current 48
telemt_desync_total 38517
telemt_desync_full_logged_total 12958
telemt_desync_suppressed_total 25559
telemt_desync_frames_bucket_total{bucket="1_2"} 9514
telemt_desync_frames_bucket_total{bucket="3_10"} 14805
telemt_desync_frames_bucket_total{bucket="gt_10"} 14198
telemt_pool_swap_total 189
telemt_pool_force_close_total 5812
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 57198
telemt_me_writer_removed_unexpected_total 1697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5269
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53477
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5300
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51386
telemt_me_writer_teardown_success_total{mode="normal"} 58746
telemt_me_writer_teardown_noop_total 57223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115969
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.236995
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115969
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1533
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8658850
telemt_user_connections_current{user="hello"} 906
telemt_user_octets_from_client{user="hello"} 216905337532 (202.01 GB)
telemt_user_octets_to_client{user="hello"} 3923253315791 (3.57 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 177968.4 (49h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10940953
telemt_connections_bad_total 950937
telemt_connections_current 660
telemt_connections_me_current 660
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344783
telemt_upstream_connect_attempt_total 77334
telemt_upstream_connect_success_total 75861
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 76065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2309
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5465
telemt_me_reconnect_success_total 2265
telemt_me_reader_eof_total 2003
telemt_me_idle_close_by_peer_total 2002
telemt_me_route_drop_no_conn_total 5319335
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8280806
telemt_me_endpoint_quarantine_total 1219
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1306
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 67
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
telemt_me_writers_active_current 87
telemt_desync_total 37848
telemt_desync_full_logged_total 12541
telemt_desync_suppressed_total 25307
telemt_desync_frames_bucket_total{bucket="1_2"} 9564
telemt_desync_frames_bucket_total{bucket="3_10"} 14475
telemt_desync_frames_bucket_total{bucket="gt_10"} 13809
telemt_pool_swap_total 185
telemt_pool_force_close_total 5722
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 726
telemt_me_draining_writers_reap_progress_total 57359
telemt_me_writer_removed_unexpected_total 2158
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5947
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53497
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5157
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51637
telemt_me_writer_teardown_success_total{mode="normal"} 59444
telemt_me_writer_teardown_noop_total 57430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116874
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.266850
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116874
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 726
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 1965
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 8272812
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 191962709937 (178.78 GB)
telemt_user_octets_to_client{user="hello"} 3441548977285 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 48248.5 (13h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11043760
telemt_connections_bad_total 666899
telemt_connections_current 1289
telemt_connections_me_current 1289
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 249467
telemt_upstream_connect_attempt_total 51086
telemt_upstream_connect_success_total 48534
telemt_upstream_connect_fail_total 1737
telemt_upstream_connect_attempts_per_request{bucket="1"} 50271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16134
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5987
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1737
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7052
telemt_me_reconnect_success_total 1041
telemt_me_reader_eof_total 653
telemt_me_idle_close_by_peer_total 652
telemt_me_route_drop_no_conn_total 25256082
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9172433
telemt_me_endpoint_quarantine_total 335
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 381
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
telemt_me_writers_active_current 45
telemt_desync_total 15712
telemt_desync_full_logged_total 4165
telemt_desync_suppressed_total 11547
telemt_desync_frames_bucket_total{bucket="1_2"} 3006
telemt_desync_frames_bucket_total{bucket="3_10"} 6354
telemt_desync_frames_bucket_total{bucket="gt_10"} 6352
telemt_pool_swap_total 49
telemt_pool_force_close_total 1711
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 452
telemt_me_draining_writers_reap_progress_total 14186
telemt_me_writer_removed_unexpected_total 930
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2051
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13023
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1405
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12475
telemt_me_writer_teardown_success_total{mode="normal"} 15074
telemt_me_writer_teardown_noop_total 14205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29279
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.299305
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29279
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 452
telemt_me_refill_failed_total 327
telemt_me_writer_restored_same_endpoint_total 681
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 9197127
telemt_user_connections_current{user="hello"} 1289
telemt_user_octets_from_client{user="hello"} 85517094332 (79.64 GB)
telemt_user_octets_to_client{user="hello"} 558845004858 (520.46 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 177975.0 (49h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10858327
telemt_connections_bad_total 915796
telemt_connections_current 975
telemt_connections_me_current 975
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 238912
telemt_upstream_connect_attempt_total 106290
telemt_upstream_connect_success_total 105181
telemt_upstream_connect_fail_total 941
telemt_upstream_connect_attempts_per_request{bucket="1"} 106122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 941
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72605
telemt_me_reconnect_success_total 2936
telemt_me_reader_eof_total 2634
telemt_me_idle_close_by_peer_total 2632
telemt_me_route_drop_no_conn_total 5238507
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8581425
telemt_me_endpoint_quarantine_total 1171
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1333
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_me_writers_active_current 47
telemt_desync_total 45800
telemt_desync_full_logged_total 15662
telemt_desync_suppressed_total 30138
telemt_desync_frames_bucket_total{bucket="1_2"} 9288
telemt_desync_frames_bucket_total{bucket="3_10"} 17524
telemt_desync_frames_bucket_total{bucket="gt_10"} 18988
telemt_pool_swap_total 181
telemt_pool_force_close_total 5415
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 651
telemt_me_draining_writers_reap_progress_total 61479
telemt_me_writer_removed_unexpected_total 2667
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6480
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57697
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4666
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56064
telemt_me_writer_teardown_success_total{mode="normal"} 64177
telemt_me_writer_teardown_noop_total 61480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125657
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.156473
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125657
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 651
telemt_me_refill_failed_total 4291
telemt_me_writer_restored_same_endpoint_total 2482
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 8584511
telemt_user_connections_current{user="hello"} 975
telemt_user_octets_from_client{user="hello"} 193648198969 (180.35 GB)
telemt_user_octets_to_client{user="hello"} 3277623309744 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 114811.2 (31h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11511279
telemt_connections_bad_total 459714
telemt_connections_current 793
telemt_connections_me_current 793
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4720275
telemt_upstream_connect_attempt_total 54321
telemt_upstream_connect_success_total 53917
telemt_upstream_connect_fail_total 393
telemt_upstream_connect_attempts_per_request{bucket="1"} 54310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 393
telemt_me_reconnect_attempts_total 48674
telemt_me_reconnect_success_total 1714
telemt_me_reader_eof_total 1378
telemt_me_idle_close_by_peer_total 1377
telemt_me_route_drop_no_conn_total 4068971
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5541751
telemt_me_endpoint_quarantine_total 747
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 871
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
telemt_desync_total 31150
telemt_desync_full_logged_total 10611
telemt_desync_suppressed_total 20539
telemt_desync_frames_bucket_total{bucket="1_2"} 6184
telemt_desync_frames_bucket_total{bucket="3_10"} 12303
telemt_desync_frames_bucket_total{bucket="gt_10"} 12663
telemt_pool_swap_total 121
telemt_pool_force_close_total 3663
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 365
telemt_me_draining_writers_reap_progress_total 40419
telemt_me_writer_removed_unexpected_total 1432
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3490
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38401
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3222
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36756
telemt_me_writer_teardown_success_total{mode="normal"} 41891
telemt_me_writer_teardown_noop_total 40426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82317
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.628035
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82317
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 365
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1519
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5534391
telemt_user_connections_current{user="hello"} 793
telemt_user_octets_from_client{user="hello"} 118341587720 (110.21 GB)
telemt_user_octets_to_client{user="hello"} 2127602852698 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 95782.2 (26h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1444965
telemt_connections_bad_total 36273
telemt_connections_current 656
telemt_connections_me_current 656
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 28405
telemt_upstream_connect_attempt_total 44856
telemt_upstream_connect_success_total 44715
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 44828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 761
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2066
telemt_me_reconnect_success_total 851
telemt_me_reader_eof_total 832
telemt_me_idle_close_by_peer_total 832
telemt_me_route_drop_no_conn_total 499900
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1281552
telemt_me_endpoint_quarantine_total 773
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 789
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 8004
telemt_desync_full_logged_total 2433
telemt_desync_suppressed_total 5571
telemt_desync_frames_bucket_total{bucket="1_2"} 1953
telemt_desync_frames_bucket_total{bucket="3_10"} 3096
telemt_desync_frames_bucket_total{bucket="gt_10"} 2955
telemt_pool_swap_total 103
telemt_pool_force_close_total 2685
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 149
telemt_me_draining_writers_reap_progress_total 37534
telemt_me_writer_removed_unexpected_total 801
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2958
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35411
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2597
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34849
telemt_me_writer_teardown_success_total{mode="normal"} 38369
telemt_me_writer_teardown_noop_total 37538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75907
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.957430
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75907
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 149
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 721
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1277484
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 25144300741 (23.42 GB)
telemt_user_octets_to_client{user="hello"} 541770490531 (504.56 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 177979.6 (49h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13191280
telemt_connections_bad_total 1564009
telemt_connections_current 1046
telemt_connections_me_current 1046
telemt_handshake_timeouts_total 379072
telemt_upstream_connect_attempt_total 67957
telemt_upstream_connect_success_total 67620
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 67821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2644
telemt_me_reconnect_success_total 1383
telemt_me_reader_eof_total 1351
telemt_me_idle_close_by_peer_total 1351
telemt_me_route_drop_no_conn_total 4466763
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9970334
telemt_me_endpoint_quarantine_total 1213
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1333
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
telemt_desync_total 41667
telemt_desync_full_logged_total 13590
telemt_desync_suppressed_total 28077
telemt_desync_frames_bucket_total{bucket="1_2"} 10013
telemt_desync_frames_bucket_total{bucket="3_10"} 15334
telemt_desync_frames_bucket_total{bucket="gt_10"} 16320
telemt_pool_swap_total 197
telemt_pool_force_close_total 5380
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 660
telemt_me_draining_writers_reap_progress_total 61305
telemt_me_writer_removed_unexpected_total 1300
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4957
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57689
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5206
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55925
telemt_me_writer_teardown_success_total{mode="normal"} 62646
telemt_me_writer_teardown_noop_total 61307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123953
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.576395
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123953
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 660
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1210
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 9937155
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 193966283840 (180.65 GB)
telemt_user_octets_to_client{user="hello"} 4400536652568 (4.00 TB)
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 177976.2 (49h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11480599
telemt_connections_bad_total 1307793
telemt_connections_current 841
telemt_connections_me_current 841
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 303347
telemt_upstream_connect_attempt_total 94475
telemt_upstream_connect_success_total 93628
telemt_upstream_connect_fail_total 640
telemt_upstream_connect_attempts_per_request{bucket="1"} 94268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2066
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 640
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10089
telemt_me_reconnect_success_total 2440
telemt_me_reader_eof_total 2277
telemt_me_idle_close_by_peer_total 2276
telemt_me_seq_mismatch_total 85
telemt_me_route_drop_no_conn_total 5626385
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8870599
telemt_me_endpoint_quarantine_total 1375
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1337
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 47
telemt_desync_total 41231
telemt_desync_full_logged_total 13227
telemt_desync_suppressed_total 28004
telemt_desync_frames_bucket_total{bucket="1_2"} 10579
telemt_desync_frames_bucket_total{bucket="3_10"} 15176
telemt_desync_frames_bucket_total{bucket="gt_10"} 15476
telemt_pool_swap_total 187
telemt_pool_force_close_total 5172
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 649
telemt_me_draining_writers_reap_progress_total 61093
telemt_me_writer_removed_unexpected_total 2311
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6297
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57187
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4701
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55921
telemt_me_writer_teardown_success_total{mode="normal"} 63484
telemt_me_writer_teardown_noop_total 61098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124582
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.304858
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124582
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 649
telemt_me_refill_failed_total 395
telemt_me_writer_restored_same_endpoint_total 1978
telemt_me_writer_restored_fallback_total 117
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 8876046
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 156660437209 (145.90 GB)
telemt_user_octets_to_client{user="hello"} 3454674466947 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 110
```