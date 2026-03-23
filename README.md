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

# Server Metrics 2026-03-23 02:01:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 104125.9 (28h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3585913
telemt_connections_bad_total 329342
telemt_connections_current 881
telemt_connections_me_current 881
telemt_handshake_timeouts_total 112922
telemt_upstream_connect_attempt_total 38811
telemt_upstream_connect_success_total 38810
telemt_upstream_connect_attempts_per_request{bucket="1"} 38810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1410
telemt_me_reconnect_success_total 613
telemt_me_reader_eof_total 630
telemt_me_idle_close_by_peer_total 630
telemt_me_route_drop_no_conn_total 2993545
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2948255
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 734
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 813
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
telemt_me_writers_active_current 44
telemt_desync_total 12705
telemt_desync_full_logged_total 4003
telemt_desync_suppressed_total 8702
telemt_desync_frames_bucket_total{bucket="1_2"} 3394
telemt_desync_frames_bucket_total{bucket="3_10"} 4625
telemt_desync_frames_bucket_total{bucket="gt_10"} 4686
telemt_pool_swap_total 115
telemt_pool_force_close_total 3530
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 662
telemt_me_draining_writers_reap_progress_total 35546
telemt_me_writer_removed_unexpected_total 607
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2537
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33265
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32016
telemt_me_writer_teardown_success_total{mode="normal"} 35802
telemt_me_writer_teardown_noop_total 35557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71359
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.755479
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71359
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 662
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 549
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2937254
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 42015675044 (39.13 GB)
telemt_user_octets_to_client{user="hello"} 803804731012 (748.60 GB)
telemt_user_unique_ips_current{user="hello"} 433
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 117492.1 (32h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4015825
telemt_connections_bad_total 371310
telemt_connections_current 219
telemt_connections_me_current 219
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100992
telemt_upstream_connect_attempt_total 73217
telemt_upstream_connect_success_total 72322
telemt_upstream_connect_fail_total 788
telemt_upstream_connect_attempts_per_request{bucket="1"} 73110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 788
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10186
telemt_me_reconnect_success_total 3673
telemt_me_reader_eof_total 3659
telemt_me_idle_close_by_peer_total 3659
telemt_me_route_drop_no_conn_total 3642685
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3189969
telemt_me_endpoint_quarantine_total 948
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 47
telemt_me_single_endpoint_outage_reconnect_success_total 45
telemt_me_single_endpoint_quarantine_bypass_total 47
telemt_me_single_endpoint_shadow_rotate_total 921
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 13006
telemt_desync_full_logged_total 7300
telemt_desync_suppressed_total 5706
telemt_desync_frames_bucket_total{bucket="1_2"} 2950
telemt_desync_frames_bucket_total{bucket="3_10"} 5107
telemt_desync_frames_bucket_total{bucket="gt_10"} 4949
telemt_pool_swap_total 110
telemt_pool_force_close_total 3119
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 48536
telemt_me_writer_removed_unexpected_total 3588
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6338
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45820
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2661
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45417
telemt_me_writer_teardown_success_total{mode="normal"} 52158
telemt_me_writer_teardown_noop_total 48537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100695
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.638558
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100695
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 3268
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 3203336
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 43220227826 (40.25 GB)
telemt_user_octets_to_client{user="hello"} 794688927302 (740.11 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 192351.9 (53h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16376896
telemt_connections_bad_total 1658926
telemt_connections_current 909
telemt_connections_me_current 909
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 398047
telemt_upstream_connect_attempt_total 86395
telemt_upstream_connect_success_total 86289
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 86306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1722
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3028
telemt_me_reconnect_success_total 1604
telemt_me_reader_eof_total 1551
telemt_me_idle_close_by_peer_total 1549
telemt_me_route_drop_no_conn_total 14050906
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13002836
telemt_me_endpoint_quarantine_total 1285
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1449
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53945
telemt_desync_full_logged_total 17152
telemt_desync_suppressed_total 36793
telemt_desync_frames_bucket_total{bucket="1_2"} 12030
telemt_desync_frames_bucket_total{bucket="3_10"} 21066
telemt_desync_frames_bucket_total{bucket="gt_10"} 20849
telemt_pool_swap_total 208
telemt_pool_force_close_total 6787
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1065
telemt_me_draining_writers_reap_progress_total 65667
telemt_me_writer_removed_unexpected_total 1492
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5571
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60866
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6317
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58880
telemt_me_writer_teardown_success_total{mode="normal"} 66437
telemt_me_writer_teardown_noop_total 65720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132157
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.826459
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132157
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1065
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1387
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 13002841
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 197238468441 (183.69 GB)
telemt_user_octets_to_client{user="hello"} 3499072227239 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 192353.3 (53h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11916979
telemt_connections_bad_total 1242924
telemt_connections_current 570
telemt_connections_me_current 570
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344711
telemt_upstream_connect_attempt_total 100755
telemt_upstream_connect_success_total 99426
telemt_upstream_connect_fail_total 876
telemt_upstream_connect_attempts_per_request{bucket="1"} 100302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42227
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3802
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 876
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4457
telemt_me_reconnect_success_total 1909
telemt_me_reader_eof_total 1773
telemt_me_idle_close_by_peer_total 1773
telemt_me_route_drop_no_conn_total 4560520
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8841546
telemt_me_endpoint_quarantine_total 1295
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1468
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
telemt_me_writers_active_current 46
telemt_desync_total 38983
telemt_desync_full_logged_total 13129
telemt_desync_suppressed_total 25854
telemt_desync_frames_bucket_total{bucket="1_2"} 9660
telemt_desync_frames_bucket_total{bucket="3_10"} 14963
telemt_desync_frames_bucket_total{bucket="gt_10"} 14360
telemt_pool_swap_total 205
telemt_pool_force_close_total 6141
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 712
telemt_me_draining_writers_reap_progress_total 63885
telemt_me_writer_removed_unexpected_total 1802
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5669
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59875
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5629
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57744
telemt_me_writer_teardown_success_total{mode="normal"} 65544
telemt_me_writer_teardown_noop_total 63910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129454
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.454076
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129454
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 712
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1632
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8779289
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 218005303012 (203.03 GB)
telemt_user_octets_to_client{user="hello"} 3969575746595 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 192317.4 (53h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11084689
telemt_connections_bad_total 981402
telemt_connections_current 529
telemt_connections_me_current 529
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345694
telemt_upstream_connect_attempt_total 85037
telemt_upstream_connect_success_total 83478
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 83683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40647
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5769
telemt_me_reconnect_success_total 2389
telemt_me_reader_eof_total 2134
telemt_me_idle_close_by_peer_total 2133
telemt_me_route_drop_no_conn_total 5340965
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8375755
telemt_me_endpoint_quarantine_total 1351
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1427
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38225
telemt_desync_full_logged_total 12662
telemt_desync_suppressed_total 25563
telemt_desync_frames_bucket_total{bucket="1_2"} 9655
telemt_desync_frames_bucket_total{bucket="3_10"} 14631
telemt_desync_frames_bucket_total{bucket="gt_10"} 13939
telemt_pool_swap_total 201
telemt_pool_force_close_total 6040
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 745
telemt_me_draining_writers_reap_progress_total 64299
telemt_me_writer_removed_unexpected_total 2284
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6416
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60099
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5469
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58259
telemt_me_writer_teardown_success_total{mode="normal"} 66515
telemt_me_writer_teardown_noop_total 64370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 130746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 130777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 130785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 130798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 130831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 130834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.838900
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 745
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2079
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8367700
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 192866084555 (179.62 GB)
telemt_user_octets_to_client{user="hello"} 3476131404421 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 62597.4 (17h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11298175
telemt_connections_bad_total 669487
telemt_connections_current 1046
telemt_connections_me_current 1046
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 279774
telemt_upstream_connect_attempt_total 59456
telemt_upstream_connect_success_total 56349
telemt_upstream_connect_fail_total 2038
telemt_upstream_connect_attempts_per_request{bucket="1"} 58387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2038
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7803
telemt_me_reconnect_success_total 1273
telemt_me_reader_eof_total 803
telemt_me_idle_close_by_peer_total 802
telemt_me_route_drop_no_conn_total 25297058
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9370311
telemt_me_endpoint_quarantine_total 467
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 501
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 16439
telemt_desync_full_logged_total 4497
telemt_desync_suppressed_total 11942
telemt_desync_frames_bucket_total{bucket="1_2"} 3123
telemt_desync_frames_bucket_total{bucket="3_10"} 6701
telemt_desync_frames_bucket_total{bucket="gt_10"} 6615
telemt_pool_swap_total 65
telemt_pool_force_close_total 2086
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 19947
telemt_me_writer_removed_unexpected_total 1159
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2643
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18407
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1779
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17861
telemt_me_writer_teardown_success_total{mode="normal"} 21050
telemt_me_writer_teardown_noop_total 19966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41016
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.943678
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41016
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 819
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 9396163
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 87559408838 (81.55 GB)
telemt_user_octets_to_client{user="hello"} 620473087594 (577.86 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 192324.1 (53h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11037788
telemt_connections_bad_total 964443
telemt_connections_current 763
telemt_connections_me_current 763
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242748
telemt_upstream_connect_attempt_total 113843
telemt_upstream_connect_success_total 112671
telemt_upstream_connect_fail_total 998
telemt_upstream_connect_attempts_per_request{bucket="1"} 113669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44162
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 998
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73045
telemt_me_reconnect_success_total 3113
telemt_me_reader_eof_total 2807
telemt_me_idle_close_by_peer_total 2805
telemt_me_route_drop_no_conn_total 5267651
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8699774
telemt_me_endpoint_quarantine_total 1302
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1456
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 46353
telemt_desync_full_logged_total 15899
telemt_desync_suppressed_total 30454
telemt_desync_frames_bucket_total{bucket="1_2"} 9423
telemt_desync_frames_bucket_total{bucket="3_10"} 17740
telemt_desync_frames_bucket_total{bucket="gt_10"} 19190
telemt_pool_swap_total 197
telemt_pool_force_close_total 5754
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 68327
telemt_me_writer_removed_unexpected_total 2831
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6945
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64253
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5005
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62573
telemt_me_writer_teardown_success_total{mode="normal"} 71198
telemt_me_writer_teardown_noop_total 68328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139526
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.286910
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139526
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 4304
telemt_me_writer_restored_same_endpoint_total 2626
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 8702715
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 194912265209 (181.53 GB)
telemt_user_octets_to_client{user="hello"} 3327154223104 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 129160.3 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11736474
telemt_connections_bad_total 482846
telemt_connections_current 546
telemt_connections_me_current 546
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4764336
telemt_upstream_connect_attempt_total 62397
telemt_upstream_connect_success_total 61937
telemt_upstream_connect_fail_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 62385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28728
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 448
telemt_me_reconnect_attempts_total 49092
telemt_me_reconnect_success_total 1859
telemt_me_reader_eof_total 1535
telemt_me_idle_close_by_peer_total 1534
telemt_me_route_drop_no_conn_total 4097425
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5640842
telemt_me_endpoint_quarantine_total 879
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 992
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 31764
telemt_desync_full_logged_total 10846
telemt_desync_suppressed_total 20918
telemt_desync_frames_bucket_total{bucket="1_2"} 6327
telemt_desync_frames_bucket_total{bucket="3_10"} 12535
telemt_desync_frames_bucket_total{bucket="gt_10"} 12902
telemt_pool_swap_total 137
telemt_pool_force_close_total 3967
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 47763
telemt_me_writer_removed_unexpected_total 1581
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3892
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45500
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3526
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43796
telemt_me_writer_teardown_success_total{mode="normal"} 49392
telemt_me_writer_teardown_noop_total 47770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97162
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.712897
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97162
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 2744
telemt_me_writer_restored_same_endpoint_total 1644
telemt_me_writer_restored_fallback_total 29
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5632980
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 120076341084 (111.83 GB)
telemt_user_octets_to_client{user="hello"} 2187238349310 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 110130.8 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1543620
telemt_connections_bad_total 36804
telemt_connections_current 434
telemt_connections_me_current 434
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31509
telemt_upstream_connect_attempt_total 52087
telemt_upstream_connect_success_total 51926
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 52059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 795
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2292
telemt_me_reconnect_success_total 939
telemt_me_reader_eof_total 927
telemt_me_idle_close_by_peer_total 927
telemt_me_route_drop_no_conn_total 521424
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1372335
telemt_me_endpoint_quarantine_total 930
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 912
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
telemt_desync_total 9332
telemt_desync_full_logged_total 2690
telemt_desync_suppressed_total 6642
telemt_desync_frames_bucket_total{bucket="1_2"} 2732
telemt_desync_frames_bucket_total{bucket="3_10"} 3546
telemt_desync_frames_bucket_total{bucket="gt_10"} 3054
telemt_pool_swap_total 119
telemt_pool_force_close_total 3019
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 44155
telemt_me_writer_removed_unexpected_total 893
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3372
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41717
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2931
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41136
telemt_me_writer_teardown_success_total{mode="normal"} 45089
telemt_me_writer_teardown_noop_total 44159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89248
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.377329
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89248
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 800
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1368132
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 26197298585 (24.40 GB)
telemt_user_octets_to_client{user="hello"} 581834843671 (541.88 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 192328.6 (53h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13358816
telemt_connections_bad_total 1612235
telemt_connections_current 684
telemt_connections_me_current 684
telemt_handshake_timeouts_total 390117
telemt_upstream_connect_attempt_total 76339
telemt_upstream_connect_success_total 75985
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 76203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3039
telemt_me_reconnect_success_total 1519
telemt_me_reader_eof_total 1503
telemt_me_idle_close_by_peer_total 1503
telemt_me_route_drop_no_conn_total 4486211
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10066487
telemt_me_endpoint_quarantine_total 1389
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1457
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 42206
telemt_desync_full_logged_total 13782
telemt_desync_suppressed_total 28424
telemt_desync_frames_bucket_total{bucket="1_2"} 10250
telemt_desync_frames_bucket_total{bucket="3_10"} 15503
telemt_desync_frames_bucket_total{bucket="gt_10"} 16453
telemt_pool_swap_total 213
telemt_pool_force_close_total 5639
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 681
telemt_me_draining_writers_reap_progress_total 69039
telemt_me_writer_removed_unexpected_total 1440
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5398
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65134
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5465
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63400
telemt_me_writer_teardown_success_total{mode="normal"} 70532
telemt_me_writer_teardown_noop_total 69041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139573
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.815840
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139573
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 681
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1333
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10033176
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 194924411248 (181.54 GB)
telemt_user_octets_to_client{user="hello"} 4445879590580 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 192325.2 (53h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11673118
telemt_connections_bad_total 1364594
telemt_connections_current 622
telemt_connections_me_current 622
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 312238
telemt_upstream_connect_attempt_total 103872
telemt_upstream_connect_success_total 102973
telemt_upstream_connect_fail_total 691
telemt_upstream_connect_attempts_per_request{bucket="1"} 103664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 691
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10639
telemt_me_reconnect_success_total 2622
telemt_me_reader_eof_total 2432
telemt_me_idle_close_by_peer_total 2431
telemt_me_seq_mismatch_total 100
telemt_me_route_drop_no_conn_total 5653678
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8981257
telemt_me_endpoint_quarantine_total 1571
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1460
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 41850
telemt_desync_full_logged_total 13479
telemt_desync_suppressed_total 28371
telemt_desync_frames_bucket_total{bucket="1_2"} 10813
telemt_desync_frames_bucket_total{bucket="3_10"} 15391
telemt_desync_frames_bucket_total{bucket="gt_10"} 15646
telemt_pool_swap_total 203
telemt_pool_force_close_total 5413
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 668
telemt_me_draining_writers_reap_progress_total 69126
telemt_me_writer_removed_unexpected_total 2474
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6777
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64910
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63713
telemt_me_writer_teardown_success_total{mode="normal"} 71687
telemt_me_writer_teardown_noop_total 69131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140818
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.496228
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140818
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 668
telemt_me_refill_failed_total 415
telemt_me_writer_restored_same_endpoint_total 2106
telemt_me_writer_restored_fallback_total 135
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 8985828
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 157529071748 (146.71 GB)
telemt_user_octets_to_client{user="hello"} 3497183047542 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 79
```