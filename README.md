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

# Server Metrics 2026-03-23 04:09:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 111756.3 (31h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3807611
telemt_connections_bad_total 372627
telemt_connections_current 1500
telemt_connections_me_current 1500
telemt_handshake_timeouts_total 126636
telemt_upstream_connect_attempt_total 41663
telemt_upstream_connect_success_total 41662
telemt_upstream_connect_attempts_per_request{bucket="1"} 41662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27033
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1446
telemt_me_reconnect_success_total 644
telemt_me_reader_eof_total 661
telemt_me_idle_close_by_peer_total 661
telemt_me_route_drop_no_conn_total 3027948
telemt_me_route_drop_channel_closed_total 1241
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3102056
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 872
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 13300
telemt_desync_full_logged_total 4231
telemt_desync_suppressed_total 9069
telemt_desync_frames_bucket_total{bucket="1_2"} 3504
telemt_desync_frames_bucket_total{bucket="3_10"} 4881
telemt_desync_frames_bucket_total{bucket="gt_10"} 4915
telemt_pool_swap_total 124
telemt_pool_force_close_total 3741
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 38147
telemt_me_writer_removed_unexpected_total 638
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2724
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35709
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3685
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34406
telemt_me_writer_teardown_success_total{mode="normal"} 38433
telemt_me_writer_teardown_noop_total 38158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76591
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 381.814227
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76591
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 578
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3090906
telemt_user_connections_current{user="hello"} 1500
telemt_user_octets_from_client{user="hello"} 43647499532 (40.65 GB)
telemt_user_octets_to_client{user="hello"} 841203758948 (783.43 GB)
telemt_user_unique_ips_current{user="hello"} 568
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 125122.2 (34h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4080807
telemt_connections_bad_total 380480
telemt_connections_current 625
telemt_connections_me_current 625
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 102977
telemt_upstream_connect_attempt_total 78402
telemt_upstream_connect_success_total 77470
telemt_upstream_connect_fail_total 825
telemt_upstream_connect_attempts_per_request{bucket="1"} 78295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 825
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10642
telemt_me_reconnect_success_total 3779
telemt_me_reader_eof_total 3760
telemt_me_idle_close_by_peer_total 3760
telemt_me_route_drop_no_conn_total 3653725
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3239180
telemt_me_endpoint_quarantine_total 1010
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 51
telemt_me_single_endpoint_outage_exit_total 51
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 983
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
telemt_me_writers_active_current 46
telemt_desync_total 13255
telemt_desync_full_logged_total 7459
telemt_desync_suppressed_total 5796
telemt_desync_frames_bucket_total{bucket="1_2"} 3010
telemt_desync_frames_bucket_total{bucket="3_10"} 5206
telemt_desync_frames_bucket_total{bucket="gt_10"} 5039
telemt_pool_swap_total 118
telemt_pool_force_close_total 3269
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 257
telemt_me_draining_writers_reap_progress_total 52157
telemt_me_writer_removed_unexpected_total 3683
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6627
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49253
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2811
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48888
telemt_me_writer_teardown_success_total{mode="normal"} 55880
telemt_me_writer_teardown_noop_total 52158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108038
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.731024
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108038
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 257
telemt_me_refill_failed_total 270
telemt_me_writer_restored_same_endpoint_total 3345
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 3253654
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 43746785903 (40.74 GB)
telemt_user_octets_to_client{user="hello"} 812687858089 (756.87 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 385
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 199982.1 (55h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16512903
telemt_connections_bad_total 1673379
telemt_connections_current 913
telemt_connections_me_current 913
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 402044
telemt_upstream_connect_attempt_total 90137
telemt_upstream_connect_success_total 90030
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 90047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1728
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3115
telemt_me_reconnect_success_total 1656
telemt_me_reader_eof_total 1611
telemt_me_idle_close_by_peer_total 1609
telemt_me_route_drop_no_conn_total 14077615
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13113171
telemt_me_endpoint_quarantine_total 1352
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1511
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
telemt_me_writers_active_current 45
telemt_desync_total 54567
telemt_desync_full_logged_total 17394
telemt_desync_suppressed_total 37173
telemt_desync_frames_bucket_total{bucket="1_2"} 12178
telemt_desync_frames_bucket_total{bucket="3_10"} 21334
telemt_desync_frames_bucket_total{bucket="gt_10"} 21055
telemt_pool_swap_total 217
telemt_pool_force_close_total 6994
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1081
telemt_me_draining_writers_reap_progress_total 69118
telemt_me_writer_removed_unexpected_total 1547
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5802
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64146
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6524
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62124
telemt_me_writer_teardown_success_total{mode="normal"} 69948
telemt_me_writer_teardown_noop_total 69171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139119
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.242573
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139119
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1081
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1438
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 13113133
telemt_user_connections_current{user="hello"} 913
telemt_user_octets_from_client{user="hello"} 198661802609 (185.02 GB)
telemt_user_octets_to_client{user="hello"} 3547637131039 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 316
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 199983.6 (55h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12057844
telemt_connections_bad_total 1274970
telemt_connections_current 969
telemt_connections_me_current 969
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 347026
telemt_upstream_connect_attempt_total 104380
telemt_upstream_connect_success_total 103036
telemt_upstream_connect_fail_total 890
telemt_upstream_connect_attempts_per_request{bucket="1"} 103926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44238
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3804
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 890
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4569
telemt_me_reconnect_success_total 1965
telemt_me_reader_eof_total 1832
telemt_me_idle_close_by_peer_total 1832
telemt_me_route_drop_no_conn_total 4578422
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8921348
telemt_me_endpoint_quarantine_total 1367
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1531
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
telemt_desync_total 39242
telemt_desync_full_logged_total 13216
telemt_desync_suppressed_total 26026
telemt_desync_frames_bucket_total{bucket="1_2"} 9724
telemt_desync_frames_bucket_total{bucket="3_10"} 15086
telemt_desync_frames_bucket_total{bucket="gt_10"} 14432
telemt_pool_swap_total 214
telemt_pool_force_close_total 6312
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 717
telemt_me_draining_writers_reap_progress_total 67154
telemt_me_writer_removed_unexpected_total 1859
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5891
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62981
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60842
telemt_me_writer_teardown_success_total{mode="normal"} 68872
telemt_me_writer_teardown_noop_total 67179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136051
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.583062
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136051
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 717
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 1682
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 8859023
telemt_user_connections_current{user="hello"} 969
telemt_user_octets_from_client{user="hello"} 218730297540 (203.71 GB)
telemt_user_octets_to_client{user="hello"} 3997577876611 (3.64 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 199947.6 (55h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11196824
telemt_connections_bad_total 1007219
telemt_connections_current 797
telemt_connections_me_current 797
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 348564
telemt_upstream_connect_attempt_total 88871
telemt_upstream_connect_success_total 87300
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 87505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42838
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5842
telemt_me_reconnect_success_total 2448
telemt_me_reader_eof_total 2194
telemt_me_idle_close_by_peer_total 2193
telemt_me_route_drop_no_conn_total 5356655
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8438284
telemt_me_endpoint_quarantine_total 1415
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1490
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 38453
telemt_desync_full_logged_total 12752
telemt_desync_suppressed_total 25701
telemt_desync_frames_bucket_total{bucket="1_2"} 9710
telemt_desync_frames_bucket_total{bucket="3_10"} 14732
telemt_desync_frames_bucket_total{bucket="gt_10"} 14011
telemt_pool_swap_total 210
telemt_pool_force_close_total 6209
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 754
telemt_me_draining_writers_reap_progress_total 67746
telemt_me_writer_removed_unexpected_total 2340
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6632
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63390
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5638
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61537
telemt_me_writer_teardown_success_total{mode="normal"} 70022
telemt_me_writer_teardown_noop_total 67817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137839
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.907419
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137839
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 754
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2130
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 8430168
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 193436002079 (180.15 GB)
telemt_user_octets_to_client{user="hello"} 3500787066597 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 70227.6 (19h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11466813
telemt_connections_bad_total 674315
telemt_connections_current 1521
telemt_connections_me_current 1521
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 298759
telemt_upstream_connect_attempt_total 64058
telemt_upstream_connect_success_total 60661
telemt_upstream_connect_fail_total 2202
telemt_upstream_connect_attempts_per_request{bucket="1"} 62863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21851
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2202
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8237
telemt_me_reconnect_success_total 1435
telemt_me_reader_eof_total 917
telemt_me_idle_close_by_peer_total 916
telemt_me_route_drop_no_conn_total 25328309
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9503690
telemt_me_endpoint_quarantine_total 541
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 561
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_warm_current 6
telemt_desync_total 16903
telemt_desync_full_logged_total 4664
telemt_desync_suppressed_total 12239
telemt_desync_frames_bucket_total{bucket="1_2"} 3258
telemt_desync_frames_bucket_total{bucket="3_10"} 6894
telemt_desync_frames_bucket_total{bucket="gt_10"} 6751
telemt_pool_swap_total 72
telemt_pool_force_close_total 2259
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 508
telemt_me_draining_writers_reap_progress_total 23153
telemt_me_writer_removed_unexpected_total 1311
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2991
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21424
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1937
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20894
telemt_me_writer_teardown_success_total{mode="normal"} 24415
telemt_me_writer_teardown_noop_total 23172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47587
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.313991
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47587
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 508
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 927
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 369
telemt_user_connections_total{user="hello"} 9530170
telemt_user_connections_current{user="hello"} 1521
telemt_user_octets_from_client{user="hello"} 89337563534 (83.20 GB)
telemt_user_octets_to_client{user="hello"} 666791812593 (621.00 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 199954.4 (55h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11162129
telemt_connections_bad_total 985088
telemt_connections_current 1039
telemt_connections_me_current 1039
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 246027
telemt_upstream_connect_attempt_total 117688
telemt_upstream_connect_success_total 116468
telemt_upstream_connect_fail_total 1043
telemt_upstream_connect_attempts_per_request{bucket="1"} 117511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46322
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1043
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73405
telemt_me_reconnect_success_total 3212
telemt_me_reader_eof_total 2906
telemt_me_idle_close_by_peer_total 2903
telemt_me_route_drop_no_conn_total 5290227
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8787933
telemt_me_endpoint_quarantine_total 1363
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1518
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 46817
telemt_desync_full_logged_total 16079
telemt_desync_suppressed_total 30738
telemt_desync_frames_bucket_total{bucket="1_2"} 9510
telemt_desync_frames_bucket_total{bucket="3_10"} 17938
telemt_desync_frames_bucket_total{bucket="gt_10"} 19369
telemt_pool_swap_total 206
telemt_pool_force_close_total 5934
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 676
telemt_me_draining_writers_reap_progress_total 71728
telemt_me_writer_removed_unexpected_total 2925
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7186
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67512
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5185
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65794
telemt_me_writer_teardown_success_total{mode="normal"} 74698
telemt_me_writer_teardown_noop_total 71729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 144272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 145691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 146110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 146383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 146417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 146420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146427
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.335570
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146427
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 676
telemt_me_refill_failed_total 4318
telemt_me_writer_restored_same_endpoint_total 2706
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8790758
telemt_user_connections_current{user="hello"} 1039
telemt_user_octets_from_client{user="hello"} 197346822517 (183.79 GB)
telemt_user_octets_to_client{user="hello"} 3360766748496 (3.06 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 450
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 136790.7 (37h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11895550
telemt_connections_bad_total 487154
telemt_connections_current 901
telemt_connections_me_current 901
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4807630
telemt_upstream_connect_attempt_total 66537
telemt_upstream_connect_success_total 66062
telemt_upstream_connect_fail_total 462
telemt_upstream_connect_attempts_per_request{bucket="1"} 66524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 462
telemt_me_reconnect_attempts_total 49232
telemt_me_reconnect_success_total 1931
telemt_me_reader_eof_total 1610
telemt_me_idle_close_by_peer_total 1609
telemt_me_route_drop_no_conn_total 4117158
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5718059
telemt_me_endpoint_quarantine_total 939
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1054
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32154
telemt_desync_full_logged_total 10986
telemt_desync_suppressed_total 21168
telemt_desync_frames_bucket_total{bucket="1_2"} 6449
telemt_desync_frames_bucket_total{bucket="3_10"} 12673
telemt_desync_frames_bucket_total{bucket="gt_10"} 13032
telemt_pool_swap_total 145
telemt_pool_force_close_total 4134
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 388
telemt_me_draining_writers_reap_progress_total 51543
telemt_me_writer_removed_unexpected_total 1652
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4103
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49144
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3690
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47409
telemt_me_writer_teardown_success_total{mode="normal"} 53247
telemt_me_writer_teardown_noop_total 51550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104797
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.766289
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104797
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 388
telemt_me_refill_failed_total 2748
telemt_me_writer_restored_same_endpoint_total 1707
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5710084
telemt_user_connections_current{user="hello"} 901
telemt_user_octets_from_client{user="hello"} 120947718384 (112.64 GB)
telemt_user_octets_to_client{user="hello"} 2225538827130 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 117761.2 (32h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1615614
telemt_connections_bad_total 37098
telemt_connections_current 632
telemt_connections_me_current 632
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 33032
telemt_upstream_connect_attempt_total 55641
telemt_upstream_connect_success_total 55467
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 55613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 817
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2414
telemt_me_reconnect_success_total 978
telemt_me_reader_eof_total 972
telemt_me_idle_close_by_peer_total 972
telemt_me_route_drop_no_conn_total 539519
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1435954
telemt_me_endpoint_quarantine_total 994
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 974
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
telemt_me_writers_active_current 43
telemt_desync_total 10092
telemt_desync_full_logged_total 2838
telemt_desync_suppressed_total 7254
telemt_desync_frames_bucket_total{bucket="1_2"} 3202
telemt_desync_frames_bucket_total{bucket="3_10"} 3804
telemt_desync_frames_bucket_total{bucket="gt_10"} 3086
telemt_pool_swap_total 127
telemt_pool_force_close_total 3197
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 47400
telemt_me_writer_removed_unexpected_total 936
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3573
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44806
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3109
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44203
telemt_me_writer_teardown_success_total{mode="normal"} 48379
telemt_me_writer_teardown_noop_total 47404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95783
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.545590
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95783
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 836
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1431633
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 26865022389 (25.02 GB)
telemt_user_octets_to_client{user="hello"} 598659901807 (557.55 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 199958.8 (55h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13457962
telemt_connections_bad_total 1627692
telemt_connections_current 1051
telemt_connections_me_current 1051
telemt_handshake_timeouts_total 393195
telemt_upstream_connect_attempt_total 80439
telemt_upstream_connect_success_total 80079
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 80302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3156
telemt_me_reconnect_success_total 1590
telemt_me_reader_eof_total 1578
telemt_me_idle_close_by_peer_total 1578
telemt_me_route_drop_no_conn_total 4503309
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10140912
telemt_me_endpoint_quarantine_total 1475
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1518
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
telemt_me_writers_active_current 41
telemt_desync_total 42556
telemt_desync_full_logged_total 13894
telemt_desync_suppressed_total 28662
telemt_desync_frames_bucket_total{bucket="1_2"} 10362
telemt_desync_frames_bucket_total{bucket="3_10"} 15630
telemt_desync_frames_bucket_total{bucket="gt_10"} 16564
telemt_pool_swap_total 222
telemt_pool_force_close_total 5791
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 689
telemt_me_draining_writers_reap_progress_total 72798
telemt_me_writer_removed_unexpected_total 1511
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5619
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68747
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5617
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67007
telemt_me_writer_teardown_success_total{mode="normal"} 74366
telemt_me_writer_teardown_noop_total 72800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 144545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 146274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 146657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 147033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 147153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 147166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 147166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 147166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 147166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 147166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 147166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 147166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 147166
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.895080
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 147166
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 689
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1399
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 10107514
telemt_user_connections_current{user="hello"} 1051
telemt_user_octets_from_client{user="hello"} 195819885528 (182.37 GB)
telemt_user_octets_to_client{user="hello"} 4498231579268 (4.09 TB)
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 199955.4 (55h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11776378
telemt_connections_bad_total 1381129
telemt_connections_current 878
telemt_connections_me_current 878
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 315920
telemt_upstream_connect_attempt_total 108178
telemt_upstream_connect_success_total 107247
telemt_upstream_connect_fail_total 723
telemt_upstream_connect_attempts_per_request{bucket="1"} 107970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2070
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 723
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10962
telemt_me_reconnect_success_total 2711
telemt_me_reader_eof_total 2513
telemt_me_idle_close_by_peer_total 2512
telemt_me_seq_mismatch_total 104
telemt_me_route_drop_no_conn_total 5671602
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9059848
telemt_me_endpoint_quarantine_total 1649
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1522
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42204
telemt_desync_full_logged_total 13592
telemt_desync_suppressed_total 28612
telemt_desync_frames_bucket_total{bucket="1_2"} 10968
telemt_desync_frames_bucket_total{bucket="3_10"} 15508
telemt_desync_frames_bucket_total{bucket="gt_10"} 15728
telemt_pool_swap_total 212
telemt_pool_force_close_total 5552
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 73058
telemt_me_writer_removed_unexpected_total 2549
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7007
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68697
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5081
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67506
telemt_me_writer_teardown_success_total{mode="normal"} 75704
telemt_me_writer_teardown_noop_total 73063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 147859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 148398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 148717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 148767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 148767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 148767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 148767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 148767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 148767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 148767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 148767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 148767
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.605037
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 148767
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 428
telemt_me_writer_restored_same_endpoint_total 2162
telemt_me_writer_restored_fallback_total 140
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 9064384
telemt_user_connections_current{user="hello"} 878
telemt_user_octets_from_client{user="hello"} 158416740152 (147.54 GB)
telemt_user_octets_to_client{user="hello"} 3542211413674 (3.22 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 117
```