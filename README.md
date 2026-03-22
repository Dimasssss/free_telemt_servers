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

# Server Metrics 2026-03-22 18:22:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 76553.9 (21h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2789038
telemt_connections_bad_total 166824
telemt_connections_current 1461
telemt_connections_me_current 1461
telemt_handshake_timeouts_total 95068
telemt_upstream_connect_attempt_total 28080
telemt_upstream_connect_success_total 28079
telemt_upstream_connect_attempts_per_request{bucket="1"} 28079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 67
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1130
telemt_me_reconnect_success_total 480
telemt_me_reader_eof_total 482
telemt_me_idle_close_by_peer_total 482
telemt_me_route_drop_no_conn_total 2312622
telemt_me_route_drop_channel_closed_total 957
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2369637
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 515
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 595
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_me_writers_warm_current 18
telemt_desync_total 10747
telemt_desync_full_logged_total 3404
telemt_desync_suppressed_total 7343
telemt_desync_frames_bucket_total{bucket="1_2"} 2885
telemt_desync_frames_bucket_total{bucket="3_10"} 3985
telemt_desync_frames_bucket_total{bucket="gt_10"} 3877
telemt_pool_swap_total 84
telemt_pool_force_close_total 2610
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 542
telemt_me_draining_writers_reap_progress_total 25628
telemt_me_writer_removed_unexpected_total 468
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1873
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23981
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2557
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23018
telemt_me_writer_teardown_success_total{mode="normal"} 25854
telemt_me_writer_teardown_noop_total 25638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51492
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 258.771677
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51492
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 542
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2365765
telemt_user_connections_current{user="hello"} 1461
telemt_user_octets_from_client{user="hello"} 34735306036 (32.35 GB)
telemt_user_octets_to_client{user="hello"} 626310490760 (583.30 GB)
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 89920.3 (24h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3735466
telemt_connections_bad_total 336427
telemt_connections_current 1400
telemt_connections_me_current 1400
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 95078
telemt_upstream_connect_attempt_total 55184
telemt_upstream_connect_success_total 54506
telemt_upstream_connect_fail_total 597
telemt_upstream_connect_attempts_per_request{bucket="1"} 55103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 597
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6321
telemt_me_reconnect_success_total 2328
telemt_me_reader_eof_total 2258
telemt_me_idle_close_by_peer_total 2258
telemt_me_route_drop_no_conn_total 3575258
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2966464
telemt_me_endpoint_quarantine_total 700
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 694
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_me_writers_active_current 96
telemt_desync_total 11739
telemt_desync_full_logged_total 6561
telemt_desync_suppressed_total 5178
telemt_desync_frames_bucket_total{bucket="1_2"} 2708
telemt_desync_frames_bucket_total{bucket="3_10"} 4595
telemt_desync_frames_bucket_total{bucket="gt_10"} 4436
telemt_pool_swap_total 84
telemt_pool_force_close_total 2522
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 212
telemt_me_draining_writers_reap_progress_total 35666
telemt_me_writer_removed_unexpected_total 2209
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4253
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33633
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2160
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33144
telemt_me_writer_teardown_success_total{mode="normal"} 37886
telemt_me_writer_teardown_noop_total 35666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73552
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.311402
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73552
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 212
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 2016
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 2977339
telemt_user_connections_current{user="hello"} 1400
telemt_user_octets_from_client{user="hello"} 38485582603 (35.84 GB)
telemt_user_octets_to_client{user="hello"} 688153654474 (640.89 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 770
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 164780.2 (45h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15691185
telemt_connections_bad_total 1500943
telemt_connections_current 2356
telemt_connections_me_current 2356
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 387510
telemt_upstream_connect_attempt_total 73724
telemt_upstream_connect_success_total 73627
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 73644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1682
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2751
telemt_me_reconnect_success_total 1406
telemt_me_reader_eof_total 1345
telemt_me_idle_close_by_peer_total 1343
telemt_me_route_drop_no_conn_total 13903206
telemt_me_route_drop_channel_closed_total 141
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12509371
telemt_me_endpoint_quarantine_total 1034
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1225
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_warm_current 25
telemt_desync_total 51412
telemt_desync_full_logged_total 16151
telemt_desync_suppressed_total 35261
telemt_desync_frames_bucket_total{bucket="1_2"} 11486
telemt_desync_frames_bucket_total{bucket="3_10"} 20037
telemt_desync_frames_bucket_total{bucket="gt_10"} 19889
telemt_pool_swap_total 177
telemt_pool_force_close_total 5997
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 971
telemt_me_draining_writers_reap_progress_total 54067
telemt_me_writer_removed_unexpected_total 1299
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4727
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49930
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5533
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 464
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48070
telemt_me_writer_teardown_success_total{mode="normal"} 54657
telemt_me_writer_teardown_noop_total 54117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108774
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 305.694756
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108774
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 971
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1210
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12510192
telemt_user_connections_current{user="hello"} 2356
telemt_user_octets_from_client{user="hello"} 181738776065 (169.26 GB)
telemt_user_octets_to_client{user="hello"} 3275338351023 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 951
telemt_user_unique_ips_recent_window{user="hello"} 299
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 164781.5 (45h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11327496
telemt_connections_bad_total 1118649
telemt_connections_current 1649
telemt_connections_me_current 1649
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 339174
telemt_upstream_connect_attempt_total 86215
telemt_upstream_connect_success_total 85013
telemt_upstream_connect_fail_total 840
telemt_upstream_connect_attempts_per_request{bucket="1"} 85853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3702
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 840
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4074
telemt_me_reconnect_success_total 1687
telemt_me_reader_eof_total 1556
telemt_me_idle_close_by_peer_total 1556
telemt_me_route_drop_no_conn_total 4435649
telemt_me_route_drop_channel_closed_total 490
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8435630
telemt_me_endpoint_quarantine_total 1042
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1245
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_warm_current 30
telemt_desync_total 37541
telemt_desync_full_logged_total 12624
telemt_desync_suppressed_total 24917
telemt_desync_frames_bucket_total{bucket="1_2"} 9240
telemt_desync_frames_bucket_total{bucket="3_10"} 14464
telemt_desync_frames_bucket_total{bucket="gt_10"} 13837
telemt_pool_swap_total 174
telemt_pool_force_close_total 5416
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 52529
telemt_me_writer_removed_unexpected_total 1595
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4859
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49109
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4918
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 498
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47113
telemt_me_writer_teardown_success_total{mode="normal"} 53968
telemt_me_writer_teardown_noop_total 52552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106520
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 102.660849
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106520
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 129
telemt_me_writer_restored_same_endpoint_total 1445
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 8374080
telemt_user_connections_current{user="hello"} 1649
telemt_user_octets_from_client{user="hello"} 209373119005 (194.99 GB)
telemt_user_octets_to_client{user="hello"} 3775426855362 (3.43 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 651
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 164748.8 (45h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10662566
telemt_connections_bad_total 918785
telemt_connections_current 1338
telemt_connections_me_current 1338
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 341574
telemt_upstream_connect_attempt_total 71276
telemt_upstream_connect_success_total 70261
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 70443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4825
telemt_me_reconnect_success_total 1955
telemt_me_reader_eof_total 1706
telemt_me_idle_close_by_peer_total 1705
telemt_me_route_drop_no_conn_total 5202288
telemt_me_route_drop_channel_closed_total 371
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8051633
telemt_me_endpoint_quarantine_total 1116
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1210
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_me_writers_warm_current 8
telemt_desync_total 37042
telemt_desync_full_logged_total 12259
telemt_desync_suppressed_total 24783
telemt_desync_frames_bucket_total{bucket="1_2"} 9375
telemt_desync_frames_bucket_total{bucket="3_10"} 14179
telemt_desync_frames_bucket_total{bucket="gt_10"} 13488
telemt_pool_swap_total 172
telemt_pool_force_close_total 5345
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 695
telemt_me_draining_writers_reap_progress_total 52765
telemt_me_writer_removed_unexpected_total 1849
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5288
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49241
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4802
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 543
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47420
telemt_me_writer_teardown_success_total{mode="normal"} 54529
telemt_me_writer_teardown_noop_total 52836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107365
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.051336
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107365
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 695
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 1691
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 8044338
telemt_user_connections_current{user="hello"} 1338
telemt_user_octets_from_client{user="hello"} 185866877073 (173.10 GB)
telemt_user_octets_to_client{user="hello"} 3350524001361 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 35025.7 (9h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10536151
telemt_connections_bad_total 645163
telemt_connections_current 2468
telemt_connections_me_current 2468
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 214268
telemt_upstream_connect_attempt_total 42265
telemt_upstream_connect_success_total 40143
telemt_upstream_connect_fail_total 1486
telemt_upstream_connect_attempts_per_request{bucket="1"} 41629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5922
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1486
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6283
telemt_me_reconnect_success_total 808
telemt_me_reader_eof_total 512
telemt_me_idle_close_by_peer_total 512
telemt_me_route_drop_no_conn_total 25097643
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8753916
telemt_me_endpoint_quarantine_total 219
telemt_me_single_endpoint_outage_enter_total 60
telemt_me_single_endpoint_outage_exit_total 60
telemt_me_single_endpoint_outage_reconnect_attempt_total 111
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 111
telemt_me_single_endpoint_shadow_rotate_total 275
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 13994
telemt_desync_full_logged_total 3649
telemt_desync_suppressed_total 10345
telemt_desync_frames_bucket_total{bucket="1_2"} 2580
telemt_desync_frames_bucket_total{bucket="3_10"} 5675
telemt_desync_frames_bucket_total{bucket="gt_10"} 5739
telemt_pool_swap_total 34
telemt_pool_force_close_total 1284
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 9851
telemt_me_writer_removed_unexpected_total 714
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1506
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9017
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1000
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 284
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8567
telemt_me_writer_teardown_success_total{mode="normal"} 10523
telemt_me_writer_teardown_noop_total 9857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20380
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.929428
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20380
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 303
telemt_me_writer_restored_same_endpoint_total 540
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 8775533
telemt_user_connections_current{user="hello"} 2468
telemt_user_octets_from_client{user="hello"} 76110912903 (70.88 GB)
telemt_user_octets_to_client{user="hello"} 406966923389 (379.02 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 846
telemt_user_unique_ips_recent_window{user="hello"} 294
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 164752.3 (45h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10502905
telemt_connections_bad_total 885509
telemt_connections_current 1882
telemt_connections_me_current 1882
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 232380
telemt_upstream_connect_attempt_total 100129
telemt_upstream_connect_success_total 99078
telemt_upstream_connect_fail_total 895
telemt_upstream_connect_attempts_per_request{bucket="1"} 99973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36765
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1321
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 895
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72182
telemt_me_reconnect_success_total 2709
telemt_me_reader_eof_total 2401
telemt_me_idle_close_by_peer_total 2399
telemt_me_route_drop_no_conn_total 5137160
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8288001
telemt_me_endpoint_quarantine_total 1094
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1226
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
telemt_me_writers_active_current 51
telemt_me_writers_warm_current 12
telemt_desync_total 43862
telemt_desync_full_logged_total 14964
telemt_desync_suppressed_total 28898
telemt_desync_frames_bucket_total{bucket="1_2"} 8903
telemt_desync_frames_bucket_total{bucket="3_10"} 16850
telemt_desync_frames_bucket_total{bucket="gt_10"} 18109
telemt_pool_swap_total 168
telemt_pool_force_close_total 5002
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 622
telemt_me_draining_writers_reap_progress_total 56003
telemt_me_writer_removed_unexpected_total 2441
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5970
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52498
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4307
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 695
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51001
telemt_me_writer_teardown_success_total{mode="normal"} 58468
telemt_me_writer_teardown_noop_total 56004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114472
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.679234
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114472
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 622
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2267
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 8291605
telemt_user_connections_current{user="hello"} 1882
telemt_user_octets_from_client{user="hello"} 188179218441 (175.26 GB)
telemt_user_octets_to_client{user="hello"} 3143112275568 (2.86 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 753
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 101588.4 (28h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11007205
telemt_connections_bad_total 425276
telemt_connections_current 1584
telemt_connections_me_current 1584
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4566808
telemt_upstream_connect_attempt_total 48282
telemt_upstream_connect_success_total 47923
telemt_upstream_connect_fail_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 48273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 350
telemt_me_reconnect_attempts_total 48247
telemt_me_reconnect_success_total 1581
telemt_me_reader_eof_total 1238
telemt_me_idle_close_by_peer_total 1237
telemt_me_route_drop_no_conn_total 3986874
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5294358
telemt_me_endpoint_quarantine_total 657
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 765
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29588
telemt_desync_full_logged_total 10012
telemt_desync_suppressed_total 19576
telemt_desync_frames_bucket_total{bucket="1_2"} 5933
telemt_desync_frames_bucket_total{bucket="3_10"} 11693
telemt_desync_frames_bucket_total{bucket="gt_10"} 11962
telemt_pool_swap_total 107
telemt_pool_force_close_total 3279
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 340
telemt_me_draining_writers_reap_progress_total 34973
telemt_me_writer_removed_unexpected_total 1299
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3118
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33187
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2856
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 423
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31694
telemt_me_writer_teardown_success_total{mode="normal"} 36305
telemt_me_writer_teardown_noop_total 34980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71285
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.275043
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71285
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 340
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1405
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5287463
telemt_user_connections_current{user="hello"} 1584
telemt_user_octets_from_client{user="hello"} 113860145416 (106.04 GB)
telemt_user_octets_to_client{user="hello"} 2012033210934 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 574
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 82559.2 (22h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1193989
telemt_connections_bad_total 24274
telemt_connections_current 1168
telemt_connections_me_current 1168
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 23285
telemt_upstream_connect_attempt_total 39660
telemt_upstream_connect_success_total 39543
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 39634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 635
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1775
telemt_me_reconnect_success_total 759
telemt_me_reader_eof_total 734
telemt_me_idle_close_by_peer_total 734
telemt_me_route_drop_no_conn_total 416267
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1058597
telemt_me_endpoint_quarantine_total 696
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 680
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
telemt_me_writers_active_current 43
telemt_desync_total 6114
telemt_desync_full_logged_total 1877
telemt_desync_suppressed_total 4237
telemt_desync_frames_bucket_total{bucket="1_2"} 1402
telemt_desync_frames_bucket_total{bucket="3_10"} 2409
telemt_desync_frames_bucket_total{bucket="gt_10"} 2303
telemt_pool_swap_total 88
telemt_pool_force_close_total 2263
telemt_me_writer_close_signal_drop_total 128
telemt_me_draining_writers_reap_progress_total 32951
telemt_me_writer_removed_unexpected_total 707
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2560
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31127
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30688
telemt_me_writer_teardown_success_total{mode="normal"} 33687
telemt_me_writer_teardown_noop_total 32954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66641
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.002405
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66641
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 128
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 645
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1054893
telemt_user_connections_current{user="hello"} 1168
telemt_user_octets_from_client{user="hello"} 19410759333 (18.08 GB)
telemt_user_octets_to_client{user="hello"} 451068982259 (420.09 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 164756.8 (45h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12803447
telemt_connections_bad_total 1487871
telemt_connections_current 1869
telemt_connections_me_current 1869
telemt_handshake_timeouts_total 360397
telemt_upstream_connect_attempt_total 62015
telemt_upstream_connect_success_total 61696
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 61888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2434
telemt_me_reconnect_success_total 1295
telemt_me_reader_eof_total 1256
telemt_me_idle_close_by_peer_total 1256
telemt_me_route_drop_no_conn_total 4356839
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9689004
telemt_me_endpoint_quarantine_total 1096
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1228
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_warm_current 19
telemt_desync_total 39816
telemt_desync_full_logged_total 12991
telemt_desync_suppressed_total 26825
telemt_desync_frames_bucket_total{bucket="1_2"} 9495
telemt_desync_frames_bucket_total{bucket="3_10"} 14706
telemt_desync_frames_bucket_total{bucket="gt_10"} 15615
telemt_pool_swap_total 182
telemt_pool_force_close_total 5019
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 638
telemt_me_draining_writers_reap_progress_total 55761
telemt_me_writer_removed_unexpected_total 1210
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4595
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52412
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4845
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50742
telemt_me_writer_teardown_success_total{mode="normal"} 57007
telemt_me_writer_teardown_noop_total 55763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112770
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.056377
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112770
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 638
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1133
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9656995
telemt_user_connections_current{user="hello"} 1869
telemt_user_octets_from_client{user="hello"} 189114535880 (176.13 GB)
telemt_user_octets_to_client{user="hello"} 4259625007912 (3.87 TB)
telemt_user_unique_ips_current{user="hello"} 669
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 164753.5 (45h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11117138
telemt_connections_bad_total 1255037
telemt_connections_current 1693
telemt_connections_me_current 1693
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 290467
telemt_upstream_connect_attempt_total 88090
telemt_upstream_connect_success_total 87317
telemt_upstream_connect_fail_total 589
telemt_upstream_connect_attempts_per_request{bucket="1"} 87906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36457
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2052
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 589
telemt_me_reconnect_attempts_total 9276
telemt_me_reconnect_success_total 2207
telemt_me_reader_eof_total 2058
telemt_me_idle_close_by_peer_total 2058
telemt_me_seq_mismatch_total 77
telemt_me_route_drop_no_conn_total 5526238
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8592673
telemt_me_endpoint_quarantine_total 1262
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 1229
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_me_writers_active_current 42
telemt_me_writers_warm_current 15
telemt_desync_total 39104
telemt_desync_full_logged_total 12630
telemt_desync_suppressed_total 26474
telemt_desync_frames_bucket_total{bucket="1_2"} 9733
telemt_desync_frames_bucket_total{bucket="3_10"} 14557
telemt_desync_frames_bucket_total{bucket="gt_10"} 14814
telemt_pool_swap_total 173
telemt_pool_force_close_total 4840
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 623
telemt_me_draining_writers_reap_progress_total 55397
telemt_me_writer_removed_unexpected_total 2085
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5794
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51759
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4384
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50557
telemt_me_writer_teardown_success_total{mode="normal"} 57553
telemt_me_writer_teardown_noop_total 55402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112955
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.929877
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112955
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 623
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 1791
telemt_me_writer_restored_fallback_total 105
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 8598455
telemt_user_connections_current{user="hello"} 1693
telemt_user_octets_from_client{user="hello"} 151295786661 (140.91 GB)
telemt_user_octets_to_client{user="hello"} 3303684451399 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 669
telemt_user_unique_ips_recent_window{user="hello"} 221
```